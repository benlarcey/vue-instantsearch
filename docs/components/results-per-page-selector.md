Vue InstantSearch Results Per Page Selector
---

A component that lets the user change the number of results to be displayed per page.

## Usage

Basic usage:

```html
<ais-results-per-page-selector :options="[20, 50, 100]"></ais-results-per-page-selector>
```

## Props

| Name    | Required | Type  | Default       | Description                       |
|:--------|:---------|:------|:--------------|:----------------------------------|
| options | false    | array | `[6, 12, 24]` | The different selectable options. |


## Slots

| Name    | Props  | Default        | Description   |
|:--------|:-------|:---------------|:--------------|
| default | option | `{{ option }}` | Option label. |

## CSS Classes

| ClassName                     | Description             |
|:------------------------------|:------------------------|
| ais-results-per-page-selector | The select input class. |
