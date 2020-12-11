# Button
> **常用的操作按钮。**

*基于Element-UI中的Button封装的使用于DNT组件库的组件*

## 使用

```html
<dnt-button label="默认按钮" @click="handleClick" />
```
```js
import { DntButton } from '@/kits'

export default {
  components: {
    DntButton
  },
}
```

## API
| 参数 | 说明 | 类型  | 默认值 | 可选值 |
| ------------ | ------------ | ------------ |------------ |------------ |
| label | 按钮文字 | `String` | - | - |
| hideLabel | 隐藏label | `Boolean` | - | - |
| type | 按钮类型 | `String` | `Primary` | `primary / secondary / tertiary` |
| icon | 左侧icon | `String` | `el-icon-arrow-right` | `iconfont` |
| loading | loading状态 | `Boolean` | false | - |
| size | 按钮大小 | `String` | - | `medium / small / mini` |
| disabled | disabled禁用状态 | `Boolean` | false | - |
| color | 按钮文字颜色 | `String` | `white` | - |
| bgColor | 按钮颜色 | `String` | `primary-color` | - |


