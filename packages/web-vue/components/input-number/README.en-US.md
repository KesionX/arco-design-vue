```yaml
meta:
  type: Component
  category: Data Entry
title: InputNumber
description: Only input boxes in numeric format are allowed.
```

*Auto translate by google.*

@import ./__demo__/basic.md

@import ./__demo__/mode.md

@import ./__demo__/size.md

@import ./__demo__/precision.md

@import ./__demo__/prefix.md

@import ./__demo__/format.md

@import ./__demo__/model.md

## API


### `<input-number>` Props

|Attribute|Description|Type|Default|
|---|---|---|:---:|
|model-value **(v-model)**|Value|`number`|`-`|
|default-value|Default value (uncontrolled mode)|`number`|`-`|
|mode|Mode (`embed`: button embedded mode, `button`: left and right button mode)|`'embed' \| 'button'`|`'embed'`|
|precision|Precision|`number`|`-`|
|step|Number change step|`number`|`1`|
|disabled|Whether to disable|`boolean`|`false`|
|error|Whether it is an error state|`boolean`|`false`|
|max|Max|`number`|`Infinity`|
|min|Min|`number`|`-Infinity`|
|formatter|Define the display value of the input|`func`|`-`|
|parser|Convert from `formatter` to number, and use with `formatter`|`func`|`-`|
|placeholder|Input prompt text|`string`|`-`|
|hide-button|Whether to hide the button (only available in `embed` mode)|`boolean`|`false`|
|size|Input size|`'mini' \| 'small' \| 'medium' \| 'large'`|`'medium'`|
|allow-clear|Whether to allow the input to be cleared|`boolean`|`false`|
|model-event|Trigger event for `v-model`|`'change' \| 'input'`|`'change'`|
### `<input-number>` Events

|Event Name|Description|Parameters|version|
|---|---|---|:---|
|change|Triggered when the value changes|value: `union`<br>event: `Event`||
|focus|Triggered when the input gets focus|event: `FocusEvent`||
|blur|Triggered when the input box loses focus|event: `FocusEvent`||
|clear|Triggered when the user clicks the clear button|event: `Event`|2.23.0|
|input|Triggered on input|value: `union`<br>inputValue: `string`<br>event: `Event`|2.27.0|
### `<input-number>` Methods

|Method|Description|Parameters|Return|
|---|---|---|:---:|
|focus|Make the input box focus|-|-|
|blur|Make the input box lose focus|-|-|


