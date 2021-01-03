# boxe-u-clearfix
Visibility helper classes from/until a specific breakpoint e.g. `u-hidden`, `u-hidden-from-mobile`.

Install using npm:
```
$ npm install --save boxe-u-clearfix
```


Import:
```scss
@import 'boxe-u-clearfix/clearfix';
```

## Usage
Boxe clearfix utility class can be added to DOM node, or extend the clearfix class with Sass to avoid the `.u-clearfix` class appearing over and over in your markup.
```html
<div class="u-clearfix">...</div>.
```

```scss
.foo {
  background-color: tomato;
  ...
  @extend %u-clearfix;
}
```
