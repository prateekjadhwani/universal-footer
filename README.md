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

To add a multi-column content, just add a `multicol` attribute to the `universal-footer` DOM as shown below

```html
<universal-footer>
  <div multicol>
	  <div col>First Column</div>
		<div col center>Middle Column with center aligned</div>
    <div col right>Last Column Aligned right</div>
  </div>
</universal-footer>
```

But, you can also combile multicols and copyright.

```html
<universal-footer>
  <div multicol>
    <div col>First Column</div>
    <div col center>Middle Column with center aligned</div>
    <div col right>Last Column Aligned right</div>
  </div>
  <div copyright>© 2015 Prateek Jadhwani</div>
</universal-footer>
```

And each column can have multiple rows with one or more titles.

```html
<universal-footer>
  <div multicol>
    <div col>
      <div row center title>Row Title</div>
      <div row center>stuff</div>
      <div row title center>More Row Title</div>
      <div row center>more stuff</div>
    </div>
    <div col center>Middle Column with center aligned</div>
    <div col right>Last Column Aligned right</div>
  </div>
  <div copyright>© 2015 Prateek Jadhwani</div>
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

To change the default footer padding:

```css
universal-footer {
  --universal-footer-padding: 40px;
}
```

To change the default margin-top or color of a title in a column:

```css
universal-footer {
  --universal-footer-col-title-margin-top: 40px;
  --universal-footer-col-title-color: #C2185B;
}
```

### More Examples

Using `universal-footer` to build github style footer. See [github-footer example](https://github.com/prateekjadhwani/universal-footer/blob/master/examples/github-footer.html).

![Github Screenshot](examples/github-screenshot.png)