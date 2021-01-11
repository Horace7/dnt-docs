# MyCard

> 统一样式的基础card。

![Card](https://tva1.sinaimg.cn/large/008eGmZEgy1gmjslzfzhmj309r04b0sq.jpg)

## 使用

```dart
import 'package:dnt_app/widgets/index.dart' show MyCard;

/// card组件
Container(
  child: MyCard(
    child: Text('card'),
    padding: EdgeInsets.all(0),
    onClick: onClick
  )
)
```

## API

| 参数 | 说明 | 类型 | 是否必填 | 默认值 |
| ------------ | ------------ | ------------ | ------------ |------------ |
| child | card中的子元素 | `Widget` | 否 | - |
| padding | card的padding | `EdgeInsets` | 否 | `EdgeInsets.all(12)` |
| onClick | 点击card触发 | `Function` | 否 | - |