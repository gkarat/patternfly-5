---
id: Split
section: layouts
cssPrefix: pf-v5-l-split
---import './Split.css'

## Examples

### Basic

```html
<div class="pf-v5-l-split">
  <div class="pf-v5-l-split__item">content</div>
  <div class="pf-v5-l-split__item pf-m-fill">pf-m-fill</div>
  <div class="pf-v5-l-split__item">content</div>
</div>

```

### With gutter

```html
<div class="pf-v5-l-split pf-m-gutter">
  <div class="pf-v5-l-split__item">content</div>
  <div class="pf-v5-l-split__item pf-m-fill">pf-m-fill</div>
  <div class="pf-v5-l-split__item">content</div>
</div>

```

### Wrappable

```html
<div class="pf-v5-l-split pf-m-gutter pf-m-wrap">
  <div class="pf-v5-l-split__item">content</div>
  <div class="pf-v5-l-split__item">content</div>
  <div class="pf-v5-l-split__item">content</div>
  <div class="pf-v5-l-split__item">content</div>
  <div class="pf-v5-l-split__item">content</div>
  <div class="pf-v5-l-split__item">content</div>
  <div class="pf-v5-l-split__item">content</div>
  <div class="pf-v5-l-split__item">content</div>
  <div class="pf-v5-l-split__item">content</div>
  <div class="pf-v5-l-split__item">content</div>
  <div class="pf-v5-l-split__item">content</div>
  <div class="pf-v5-l-split__item">content</div>
  <div class="pf-v5-l-split__item">content</div>
  <div class="pf-v5-l-split__item">content</div>
</div>

```

## Documentation

### Overview

The split layout is designed to position items horizontally, with one item filling the available horizontal space.

### Usage

| Class | Applied to | Outcome |
| -- | -- | -- |
| `.pf-v5-l-split` | `<div>`, `<section>`, or `<article>` | Initiates the split layout. |
| `.pf-v5-l-split__item` | `<div>` | Initiates a split item. **Required** |
| `.pf-m-gutter` | `.pf-v5-l-split` | Adds space between children by using the globally defined gutter value. |
| `.pf-m-wrap` | `.pf-v5-l-split` | Sets the split layout to wrap. |
| `.pf-m-fill` | `.pf-v5-l-split__item` | Specifies which item(s) should fill the avaiable horizontal space. |
