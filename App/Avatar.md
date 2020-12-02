# MyToast

> 头像的展示,当图片加载失败或者url为false时,会展示名称前两个字的默认头像。

## 使用

```dart
import 'package:dnt_app/widgets/index.dart' show MyAvatar;

MyAvatar(
  url: item[_urlField],
  defaultName: item[_nameField],
)
```

## API

| 参数 | 说明 | 类型 | 必填 | 默认值 |
| ------------ | ------------ | ------------ | ------------ |------------ |
| url | 头像图片的url | `String` | 是 | - |
| defaultName | 当url为false或加载失败时,用前两个字作为默认头像 | `String` | 是 | - |
| customRadius | 自定义半径 | `double` | 否 | 12 |
| widget | 头像的宽 | `double` | 否 | 24 |
| height | 头像的高 | `double` | 否 | 24 |
| icon | 头像四个角落可以展示Icon | `IconData` | 否 | - |
| iconColor | 头像展示Icon的颜色 | `Color` | 否 | - |
| iconAlign | Icon的位置 | `Alignment` | 否 | `Alignment.bottomRight(右下角)` |