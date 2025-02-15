---
category: Components
type: Data Entry
title: AutoComplete
cover: https://gw.alipayobjects.com/zos/alicdn/qtJm4yt45/AutoComplete.svg
---

Autocomplete function of input field.

## When To Use

When there is a need for autocomplete functionality.

## API

### AutoComplete

| 参数 | 说明 | 类型 | 默认值 | 版本 |
| --- | --- | --- | --- | --- |
| `Backfill` | backfill selected item the input when using keyboard | `boolean` | `false` |
| `Options` | Data source for autocomplete | `AutocompleteDataSource` | - |
| `Disabled` | Set disabled | `bool` | - |
| `Placeholder` | Placeholder text | `string` | - |
| `DefaultActiveFirstOption` | Whether active first option by default | `boolean` | `true` |
| `Width` | Custom width, unit px | `int` | auto |
| `OverlayClassName` | Class name of the dropdown root element | `string` | - |
| `OverlayStyle` | Style of the dropdown root element | `object` | - |
| `CompareWith` | `(o1: object, o2: object) => bool` | `(o1: object, o2: object) => o1===o2` |
| `PopupContainerSelector` | The selector of the container for dropdown element. | `string` | `'body'` |

### AutoCompleteOption

| 属性 | 说明 | 类型 | 默认值 |
| --- | --- | --- | --- |
| `Value` | bind ngModel of the trigger element | `object` | - |
| `Label` | display value of the trigger element | `string` | - |
| `Disabled` | disabled option | `boolean` | `false` |

