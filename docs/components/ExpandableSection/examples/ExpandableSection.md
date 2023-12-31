---
id: Expandable section
section: components
cssPrefix: pf-v5-c-expandable-section
---## Examples

### Hidden

```html
<div class="pf-v5-c-expandable-section">
  <button
    type="button"
    class="pf-v5-c-expandable-section__toggle"
    aria-expanded="false"
  >
    <span class="pf-v5-c-expandable-section__toggle-icon">
      <i class="fas fa-angle-right" aria-hidden="true"></i>
    </span>
    <span class="pf-v5-c-expandable-section__toggle-text">Show more</span>
  </button>
  <div
    class="pf-v5-c-expandable-section__content"
    hidden
  >This content is visible only when the component is expanded.</div>
</div>

```

### Expanded

```html
<div class="pf-v5-c-expandable-section pf-m-expanded">
  <button
    type="button"
    class="pf-v5-c-expandable-section__toggle"
    aria-expanded="true"
  >
    <span class="pf-v5-c-expandable-section__toggle-icon">
      <i class="fas fa-angle-right" aria-hidden="true"></i>
    </span>
    <span class="pf-v5-c-expandable-section__toggle-text">Show less</span>
  </button>
  <div
    class="pf-v5-c-expandable-section__content"
  >This content is visible only when the component is expanded.</div>
</div>

```

### Disclosure variation (hidden)

```html
<div class="pf-v5-c-expandable-section pf-m-display-lg pf-m-limit-width">
  <button
    type="button"
    class="pf-v5-c-expandable-section__toggle"
    aria-expanded="false"
  >
    <span class="pf-v5-c-expandable-section__toggle-icon">
      <i class="fas fa-angle-right" aria-hidden="true"></i>
    </span>
    <span class="pf-v5-c-expandable-section__toggle-text">Show more</span>
  </button>
  <div
    class="pf-v5-c-expandable-section__content"
    hidden
  >This content is visible only when the component is expanded.</div>
</div>

```

### Disclosure variation (expanded)

```html
<div
  class="pf-v5-c-expandable-section pf-m-expanded pf-m-display-lg pf-m-limit-width"
>
  <button
    type="button"
    class="pf-v5-c-expandable-section__toggle"
    aria-expanded="true"
  >
    <span class="pf-v5-c-expandable-section__toggle-icon">
      <i class="fas fa-angle-right" aria-hidden="true"></i>
    </span>
    <span class="pf-v5-c-expandable-section__toggle-text">Show less</span>
  </button>
  <div
    class="pf-v5-c-expandable-section__content"
  >This content is visible only when the component is expanded.</div>
</div>

```

### Detached toggle

```html
<div class="pf-v5-l-stack pf-m-gutter">
  <div class="pf-v5-l-stack__item">
    <div class="pf-v5-c-expandable-section pf-m-expanded pf-m-detached">
      <div
        class="pf-v5-c-expandable-section__content"
        id="detached-toggle-content"
      >This content is visible only when the component is expanded.</div>
    </div>
  </div>

  <div class="pf-v5-l-stack__item">
    <div class="pf-v5-c-expandable-section pf-m-expanded pf-m-detached">
      <button
        type="button"
        class="pf-v5-c-expandable-section__toggle"
        aria-expanded="true"
        aria-controls="detached-toggle-content"
      >
        <span class="pf-v5-c-expandable-section__toggle-icon pf-m-expand-top">
          <i class="fas fa-angle-right" aria-hidden="true"></i>
        </span>
        <span class="pf-v5-c-expandable-section__toggle-text">Show less</span>
      </button>
    </div>
  </div>
</div>

```

### Indented

```html
<div class="pf-v5-c-expandable-section pf-m-expanded pf-m-indented">
  <button
    type="button"
    class="pf-v5-c-expandable-section__toggle"
    aria-expanded="true"
  >
    <span class="pf-v5-c-expandable-section__toggle-icon">
      <i class="fas fa-angle-right" aria-hidden="true"></i>
    </span>
    <span class="pf-v5-c-expandable-section__toggle-text">Show less</span>
  </button>
  <div
    class="pf-v5-c-expandable-section__content"
  >This content is visible only when the component is expanded.</div>
</div>

```

### Truncate expansion

```html
<div class="pf-v5-c-expandable-section pf-m-truncate">
  <div
    class="pf-v5-c-expandable-section__content"
  >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus finibus, diam vitae eleifend consequat, metus sapien posuere quam, ut tincidunt nunc enim eget sapien. Mauris ac dui imperdiet dolor dignissim efficitur laoreet quis erat. Proin turpis leo, malesuada eget urna et, tristique mollis odio. Ut mattis nulla lorem, elementum hendrerit nunc molestie vitae. Proin massa sem, bibendum id urna in, viverra porta neque. Ut ut mi ac lacus rhoncus mollis id quis sem. Suspendisse non justo elementum, dictum eros nec, hendrerit sapien. Mauris aliquet, est sit amet tincidunt vehicula, purus est hendrerit arcu, vitae egestas odio lorem ut lacus. In et neque non metus viverra rhoncus quis non purus. Integer id venenatis tortor. Nulla sollicitudin convallis tellus, at porta eros volutpat in. Curabitur rhoncus rhoncus nisi, sit amet tincidunt dolor efficitur vitae. Integer purus neque, porta non odio lobortis, accumsan elementum risus. Pellentesque viverra id lacus a cursus. Etiam eu pulvinar risus. Etiam ultrices nec urna id consequat.</div>
  <button
    type="button"
    class="pf-v5-c-expandable-section__toggle"
    aria-expanded="false"
  >
    <span class="pf-v5-c-expandable-section__toggle-text">Show more</span>
  </button>
</div>

```

### Truncate expansion expanded

```html
<div class="pf-v5-c-expandable-section pf-m-expanded pf-m-truncate">
  <div
    class="pf-v5-c-expandable-section__content"
  >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus finibus, diam vitae eleifend consequat, metus sapien posuere quam, ut tincidunt nunc enim eget sapien. Mauris ac dui imperdiet dolor dignissim efficitur laoreet quis erat. Proin turpis leo, malesuada eget urna et, tristique mollis odio. Ut mattis nulla lorem, elementum hendrerit nunc molestie vitae. Proin massa sem, bibendum id urna in, viverra porta neque. Ut ut mi ac lacus rhoncus mollis id quis sem. Suspendisse non justo elementum, dictum eros nec, hendrerit sapien. Mauris aliquet, est sit amet tincidunt vehicula, purus est hendrerit arcu, vitae egestas odio lorem ut lacus. In et neque non metus viverra rhoncus quis non purus. Integer id venenatis tortor. Nulla sollicitudin convallis tellus, at porta eros volutpat in. Curabitur rhoncus rhoncus nisi, sit amet tincidunt dolor efficitur vitae. Integer purus neque, porta non odio lobortis, accumsan elementum risus. Pellentesque viverra id lacus a cursus. Etiam eu pulvinar risus. Etiam ultrices nec urna id consequat.</div>
  <button
    type="button"
    class="pf-v5-c-expandable-section__toggle"
    aria-expanded="true"
  >
    <span class="pf-v5-c-expandable-section__toggle-text">Show less</span>
  </button>
</div>

```

## Documentation

### Accessibility

| Attribute | Applied to | Outcome |
| -- | -- | -- |
| `aria-expanded="true"` | `.pf-v5-c-expandable-section__toggle` | Indicates that the expandable section content is visible. **Required** |
| `aria-expanded="false"` | `.pf-v5-c-expandable-section__toggle` | Indicates the the expandable section content is hidden. **Required** |
| `hidden` | `.pf-v5-c-expandable-section__content` | Indicates that the expandable section content element is hidden. Use with `aria-expanded="false"` **Required** |
| `aria-hidden="true"` | `.pf-v5-c-expandable-section__toggle-icon` | Hides the icon from screen readers. **Required** |
| `aria-controls="[id of content element]"` | `.pf-v5-c-expandable-section.pf-m-detached .pf-v5-c-expandable-section__toggle` | Identifies the element controlled by the toggle button. **Required** |
| `id` | `.pf-v5-c-expandable-section.pf-m-detached .pf-v5-c-expandable-section__content` | Gives the content an `id` for use with `aria-controls` on `.pf-v5-c-expandable-section__toggle`. **Required** |

### Usage

| Class | Applied to | Outcome |
| -- | -- | -- |
| `.pf-v5-c-expandable-section` | `<div>` | Initiates the expandable section component. **Required** |
| `.pf-v5-c-expandable-section__toggle` | `<button>` | Initiates the expandable section toggle. **Required** |
| `.pf-v5-c-expandable-section__toggle-text` | `<span>` | Initiates the expandable toggle text. **Required** |
| `.pf-v5-c-expandable-section__toggle-icon` | `<span>` | Initiates the expandable toggle icon. **Required** |
| `.pf-v5-c-expandable-section__content` | `<div>` | Initiates the expandable section content. **Required** |
| `.pf-m-expanded` | `.pf-v5-c-expandable-section` | Modifies the component for the expanded state. |
| `.pf-m-display-lg` | `.pf-v5-c-expandable-section` | Modifies the styling of the component to have large display styling. |
| `.pf-m-detached` | `.pf-v5-c-expandable-section` | Indicates that the expandable section toggle and content are detached from one another, so you can move them around independently in the markup. |
| `.pf-m-indented` | `.pf-v5-c-expandable-section` | Indicates that the expandable section content is indented and is aligned with the start of the title text to provide visual hierarchy. |
| `.pf-m-truncate` | `.pf-v5-c-expandable-section` | Indicates that the expandable section content is truncated by default, and not truncated when expanded. |
| `.pf-m-active` | `.pf-v5-c-expandable-section__toggle` | Forces display of the active state of the toggle. |
| `.pf-m-expand-top` | `.pf-v5-c-expandable-section__toggle-icon` | Modifies the toggle icon to point up when expanded. |
| `--pf-v5-c-expandable-section--m-truncate__content--LineClamp` | `.pf-v5-c-expandable-section.pf-m-truncate` | Modifies the number of lines to show before truncating. |
