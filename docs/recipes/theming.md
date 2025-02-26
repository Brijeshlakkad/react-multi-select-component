# 💅 Themeing

You can override CSS variables to customize the appearance

```css
.rmsc {
  --rmsc-main: #4285f4;
  --rmsc-hover: #f1f3f5;
  --rmsc-selected: #e2e6ea;
  --rmsc-border: #ccc;
  --rmsc-gray: #aaa;
  --rmsc-bg: #fff;
  --rmsc-p: 10px; /* Spacing */
  --rmsc-radius: 4px; /* Radius */
  --rmsc-h: 38px; /* Height */
}
```

<Callout emoji="💡">
  use `!important` if CSS variables are not getting applied
</Callout>

## Dark Mode

if you are using any UI framework that supports dark mode and want to extend the same to `react-multi-select-component` you can do that by passing override class and styles like below

```jsx
<MultiSelect className="dark" {...otherProps} />
```

```css
.rmsc.dark {
  --rmsc-main: #4285f4;
  --rmsc-hover: #0e0c0a;
  --rmsc-selected: #1d1915;
  --rmsc-border: #333333;
  --rmsc-gray: #555555;
  --rmsc-bg: #000000;
  color: #fff;
}
```
