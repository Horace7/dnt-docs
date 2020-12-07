# ImagePreview

> 头像的展示,当图片加载失败或者url为false时,会展示名称前两个字的默认头像。

## 使用

```dart
import 'package:dnt_app/widgets/index.dart' show ImagePreview;

ImagePreview.show(
  context,
  imagesList, // 需要预览的图片列表
  currentIndex, // 展示图片的index
)
```

## API

| 参数 | 说明 | 类型 | 必填 | 默认值 |
| ------------ | ------------ | ------------ | ------------ |------------ |
| context | Context | `BuildContext` | 是 | - |
| imgs | 预览的图片列表 | `List` | 是 | - |
| index | 默认展示图片的index | `int` | 是 | 0 |
| fieldName | 自定义图片名称字段 | `String` | 否 | `resourceName` |
| fieldUrl | 自定义图片URL字段 | `String` | 否 | `resourceUrl` |
| showDelete | 是否展示删除按钮 | `bool` | 否 | `false` |
| deleteCb | 展示删除按钮并点击时的回调 | `Function` | 否 | - |