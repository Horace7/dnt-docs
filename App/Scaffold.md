# MyScaffold

> **一个基础的、通用的页面UI脚手架Widget**

*基于Flutter原生MaterialUI的二次封装*


## 使用

```dart
import 'package:dnt_app/widgets/index.dart' show MyScaffold;

/// 基础用法
Widget build(BuildContext context) {
  return MyScaffold(
    title: '页面标题',
    body: Container(
      child: Text('MyScaffold'),
    ),
  );
}
```

## API

| 参数 | 说明 | 类型 | 可选值 | 默认值 |
| ------------ | ------------ | ------------ | ------------ |------------ |
| title | 页面标题(如果使用自定义AppBar则title不生效) | `String` | - | - |
| body | 主体部分内容 | `Widget` | - | - |
| backgroundColor | 主体部分背景颜色 | `Color` | - | `Colors.white` |
| appBar | 自定义AppBar | `AppBar/MyAppBar` | - | - |
| appBarColor | 自定义AppBar颜色(如果使用自定义AppBar则color不生效) | `AppBar` | - | - |
| backType | appbar返回按钮的类型 | `String` | back(返回), none(不展示), close(关闭) | `back` |
| rightActions | AppBar右侧的操作按钮 | `List<Widget>` | - | - |
