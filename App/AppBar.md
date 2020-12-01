# MyAppBar

> **一个基础的、通用的页面Appbar Widget**

*基于Flutter原生MaterialUI的二次封装*


## 使用

```dart
import 'package:dnt_app/widgets/index.dart' show MyAppBar, AppBarBackType;

/// 基础用法
Widget build(BuildContext context) {
  return MyScaffold(
    appBar: MyAppBar(
        title: Text('Title'),
        elevation: 0,
        leadingType: AppBarBackType.None,
    ),
  );
}
```

## API

同`AppBar`



