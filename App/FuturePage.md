# MyFuturePage

> 适用于大部分首次加载需要 loading 的页面。
> 只需要传入请求数据的方法,无需关心 loading 的页面和状态。

![Loading](https://tva1.sinaimg.cn/large/008eGmZEgy1gmjszu5dqfj309y0eg746.jpg)
![](https://tva1.sinaimg.cn/large/008eGmZEgy1gmjt0lp3wcj30a40elq3k.jpg)

## 使用

```dart
import 'package:dnt_app/widgets/index.dart' show MyFuturePage;

/// card组件
Container(
  child: Expanded(
    child: MyFuturePage(
      loading: loadingStatus,
      child: _renderList,
    ),
  ),
)
```

## Tips

- 用 MyFuturePage 时在子组件调用请求接口的方法, **父组件只需要传入,不用调用**
- 如果传入 loading 参数,代表 loading 状态由父组件维护,则不需要传 method, **自行在父组件调用**

## API

| 参数    | 说明            | 类型         | 是否必填 | 默认值               |
| ------- | --------------- | ------------ | -------- | -------------------- |
| child   | 需要渲染的child, 如果传入`method`方法,则回调中的参数为`method`的返回值 | `Widget Function([dynamic])`     | 否       | `Container`    |
| method |  异步方法, 返回`child`中需要渲染的数据 | `Future<dynamic> Function([dynamic])`   | 否       | -   |
| loading | 加载的状态, 如果为`true`,则不要传入`method` | `Boolean` | 否       | `false` |
