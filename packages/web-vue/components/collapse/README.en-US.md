```yaml
meta:
  type: Component
  category: Data Display
title: Collapse
description: The content area that can be collapsed/expanded.
```

*Auto translate by google.*

@import ./__demo__/basic.md

@import ./__demo__/accordion.md

@import ./__demo__/border-less.md

@import ./__demo__/icon-position.md

@import ./__demo__/destroy.md

## API


### `<collapse>` Props

|Attribute|Description|Type|Default|version|
|---|---|---|:---:|:---|
|active-key **(v-model)**|The `key` of the currently expanded panel|`(string \| number)[]`|`-`||
|default-active-key|The `key` of the panel expanded by default (uncontrolled mode)|`(string \| number)[]`|`[]`||
|accordion|Whether to enable accordion mode|`boolean`|`false`||
|expand-icon-position|The location where the expand icon is displayed|`'left' \| 'right'`|`'left'`||
|bordered|Whether to show the border|`boolean`|`true`||
|destroy-on-hide|Whether to destroy content when hidden|`boolean`|`false`|2.27.0|
### `<collapse>` Events

|Event Name|Description|Parameters|
|---|---|---|
|change|Emitted when the expanded panel changes|activeKey: `(string \| number)[]`<br>event: `Event`|




### `<collapse-item>` Props

|Attribute|Description|Type|Default|version|
|---|---|---|:---:|:---|
|key|The id of the panel, corresponding to the value in `activeKey`|`string`|`-`||
|header|The title of the panel|`string`|`-`||
|disabled|Whether to disable|`boolean`|`false`||
|show-expand-icon|Whether to show the expand icon|`boolean`|`true`||
|destroy-on-hide|Whether to destroy content when hidden|`boolean`|`false`|2.27.0|
### `<collapse-item>` Slots

|Slot Name|Description|Parameters|
|---|---|---|
|header|The title of the panel|-|
|extra|Extra Content|-|


