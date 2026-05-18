# css-animation-iteration-count

Functional CSS for animation-iteration-count

## Filesize

| File | Size |
|------|------|
| `dist/animation-iteration-count.css` | 1381 bytes |
| `dist/animation-iteration-count.min.css` | 1043 bytes (200 Gzipped) |

## Install

```sh
npm install css-animation-iteration-count
```

## Usage

### Import

```css
@import "css-animation-iteration-count";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-animation-iteration-count/dist/animation-iteration-count.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-animation-iteration-count/dist/animation-iteration-count.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.a-cnt0` | `animation-iteration-count: 0;` |
| `.a-cnt1` | `animation-iteration-count: 1;` |
| `.a-cnt2` | `animation-iteration-count: 2;` |
| `.a-cnt3` | `animation-iteration-count: 5;` |
| `.a-cnt4` | `animation-iteration-count: 10;` |
| `.a-cnt-inf` | `animation-iteration-count: infinite;` |
| `.a-cnt0-s` | `animation-iteration-count: 0;` |
| `.a-cnt1-s` | `animation-iteration-count: 1;` |
| `.a-cnt2-s` | `animation-iteration-count: 2;` |
| `.a-cnt3-s` | `animation-iteration-count: 5;` |
| `.a-cnt4-s` | `animation-iteration-count: 10;` |
| `.a-cnt-inf-s` | `animation-iteration-count: infinite;` |
| `.a-cnt0-m` | `animation-iteration-count: 0;` |
| `.a-cnt1-m` | `animation-iteration-count: 1;` |
| `.a-cnt2-m` | `animation-iteration-count: 2;` |
| `.a-cnt3-m` | `animation-iteration-count: 5;` |
| `.a-cnt4-m` | `animation-iteration-count: 10;` |
| `.a-cnt-inf-m` | `animation-iteration-count: infinite;` |
| `.a-cnt0-l` | `animation-iteration-count: 0;` |
| `.a-cnt1-l` | `animation-iteration-count: 1;` |
| `.a-cnt2-l` | `animation-iteration-count: 2;` |
| `.a-cnt3-l` | `animation-iteration-count: 5;` |
| `.a-cnt4-l` | `animation-iteration-count: 10;` |
| `.a-cnt-inf-l` | `animation-iteration-count: infinite;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.a-cnt0-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/animation-iteration-count.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/animation-iteration-count.css` — formatted
- `dist/animation-iteration-count.min.css` — minified

## License

MIT
