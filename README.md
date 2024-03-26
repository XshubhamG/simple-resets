# Simple CSS resets

This is a simple CSS reset. It's not meant to be a full reset. It's just meant to get you started quickly.

## Installation

```bash
npm install simple-resets
```

## Usage

Simply include the following in your stylesheet

```css
@import 'simple-resets';
```

Or use the `@use` directive

```css
@use 'simple-resets';
```

## Examples

### Box sizing

```css
*,
*::after,
*::before {
  box-sizing: border-box;
}
```

### Slightly bigger line-height

```css
body {
  line-height: 1.5;
  -webkit-font-smoothing: antialiased;
}
```

### Hide content from screen readers

```css
.sr-only {
  border: 0 !important;
  clip: rect(1px, 1px, 1px, 1px) !important;
  -webkit-clip-path: inset(50%) !important;
  clip-path: inset(50%) !important;
  height: 1px !important;
  margin: -1px !important;
  overflow: hidden !important;
  padding: 0 !important;
  position: absolute !important;
  width: 1px !important;
  white-space: nowrap !important;
}
```

### Remove default list styles

```css
ul,
ol {
  list-style: none;
}
```

### Remove default form styles

```css
input,
button,
textarea,
select {
  font: inherit;
}
```

### Remove default button styles

```css
button {
  background: none;
  border: none;
  cursor: pointer;
}
```

### Stop words from overflowing

```css
p,
h1,
h2,
h3,
h4,
h5,
h6 {
  overflow-wrap: break-word;
}
```

### Set default image styles

```css
img,
picture,
video,
canvas,
svg {
  display: block;
  max-width: 100%;
}
```

### Set default link styles

```css
a {
  text-decoration: none;
  font: inherit;
  color: inherit;
  &:hover {
    text-decoration: underline;
  }
}
```

## License

MIT

## Author

[Shubham Giri](https://github.com/xshubhamg)
