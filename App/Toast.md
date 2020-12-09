# MyToast

> 常用于主动操作后的反馈提示。

*基于OkToast的二次封装*

<image src='https://raw.githubusercontent.com/CccFans/images/master/img/20181207161742.png' width=400/>

## 使用

```dart
import 'package:dnt_app/widgets/index.dart' show MyToast;

/// 展示弹窗
MyToast.show('some text');
/// 关闭弹窗
MyToast.cancelToast('some text');
```

## API

| 参数 | 说明 | 类型 | 是否必填 | 默认值 |
| ------------ | ------------ | ------------ | ------------ |------------ |
| 第一个参数 | 需要弹窗展示的文字 | `String` | 是 | - |
| duration | 延迟多少毫秒关闭弹窗 | `int` | 否 | `1500` |