# fancy-checkboxes-radios
Tired of styling the same checkboxes and radios? Me too... This is a mixin starting point for fancy checkbox and radio inputs. See it in action [on codepen](https://codepen.io/erwstout/pen/xrNEBJ?editors=1100)

## Usage
### `@include f1-radio($size, $background, $border);`
### `@include f1-checkbox($size, $background, $border);`

These mixins accept 3 parameters: 
- `$size` ex: `24px`
- `$background` ex: `#fff`
- `$border` ex: `2px solid #ecc` or `none`

The mixin will handle checked states for you as well.

### Using in your scss
Adding it to your theme stylesheet would look like this:

```scss
input[type=radio] {
  @include f1-radio(24px, #fff, 2px solid #eee);
}
```
