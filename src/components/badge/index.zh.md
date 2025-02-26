# Badge 徽标

在右上角展示数字、文字、小红点。

## 何时使用

适用于产品化的新消息、新功能、新服务等内容的提醒，通过醒目视觉形式吸引用户处理。

<code src="./demos/demo1.tsx"></code>

### 属性

| 属性     | 说明                                                                                            | 类型                                  | 默认值  |
| -------- | ----------------------------------------------------------------------------------------------- | ------------------------------------- | ------- |
| content  | 徽标内容：如果传 `null` `undefined` `''` 或不传，则不显示徽标；如果传 `Badge.dot`，会显示小红点 | `React.ReactNode \| typeof Badge.dot` | -       |
| color    | 徽标背景色，等效于设置 `--color` CSS 变量                                                       | `string`                              | -       |
| bordered | 是否增加描边                                                                                    | `boolean`                             | `false` |

### CSS 变量

| 属性    | 说明                       | 默认值                   | 全局变量            |
| ------- | -------------------------- | ------------------------ | ------------------- |
| --right | 相对于最右边，向左的偏移量 | `0`                      |                     |
| --top   | 相对于最上边，向下的偏移量 | `0`                      |                     |
| --color | 徽标背景色                 | `var(--adm-badge-color)` | `--adm-badge-color` |
