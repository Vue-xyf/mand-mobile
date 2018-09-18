---
title: CellItem
preview: https://didi.github.io/mand-mobile/examples/#/cell-item
---

Arrange vertically and display current contents, status and other allowable operations.

### Import

```javascript
import { CellItem } from 'mand-mobile'

Vue.component(CellItem.name, CellItem)
```

### Code Examples
<!-- DEMO -->

### API

#### CellItem Props
|Props | Description | Type | Default | Note|
|----|-----|------|------|------|
|title|title|String|-|-|
|brief|description text|String|-|-|
|addon|help info text|String|-|-|
|disabled|disable item operation|Boolean|false|-|
|arrow|arrow indicator|Boolean|false|-|

#### CellItem Events
##### @click(event)
click event when not disabled

#### CellItem Slots

##### default
default content slot

##### start
start content slot

##### addon
addon content slot

##### children
extra children slot