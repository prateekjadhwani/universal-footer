# universal-footer
A Polymer 1.0 element that can be used as a footer in a webapp.

### Installation

You can install this element with the help of bower.

```shell
bower install --save universal-footer
```

### Using the footer

As we all know a footer requires a bunch of predefined stuff like copyright text, social links etc. Example

```html
<universal-footer>
  <div copyright>2015 Prateek Jadhwani</div>
</universal-footer>
```

### Styling the footer

To change the background color of the footer:

```css
universal-footer {
  --universal-footer-background-color: #e91e63;
}
```

To change the default text color in footer:

```css
universal-footer {
  --universal-footer-text-color: #f8bbd0;
}
```