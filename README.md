# css-animation-iteration-count

Functional CSS for animation-iteration-count

## Filesize

| File | Size |
|------|------|
| `dist/animation-iteration-count.css` | 1417 bytes |
| `dist/animation-iteration-count.min.css` | 1079 bytes (199 Gzipped) |

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
| `.a-count0` | `animation-iteration-count: 0;` |
| `.a-count1` | `animation-iteration-count: 1;` |
| `.a-count2` | `animation-iteration-count: 2;` |
| `.a-count3` | `animation-iteration-count: 5;` |
| `.a-count4` | `animation-iteration-count: 10;` |
| `.a-count5` | `animation-iteration-count: infinite;` |
| `.a-count0-s` | `animation-iteration-count: 0;` |
| `.a-count1-s` | `animation-iteration-count: 1;` |
| `.a-count2-s` | `animation-iteration-count: 2;` |
| `.a-count3-s` | `animation-iteration-count: 5;` |
| `.a-count4-s` | `animation-iteration-count: 10;` |
| `.a-count5-s` | `animation-iteration-count: infinite;` |
| `.a-count0-m` | `animation-iteration-count: 0;` |
| `.a-count1-m` | `animation-iteration-count: 1;` |
| `.a-count2-m` | `animation-iteration-count: 2;` |
| `.a-count3-m` | `animation-iteration-count: 5;` |
| `.a-count4-m` | `animation-iteration-count: 10;` |
| `.a-count5-m` | `animation-iteration-count: infinite;` |
| `.a-count0-l` | `animation-iteration-count: 0;` |
| `.a-count1-l` | `animation-iteration-count: 1;` |
| `.a-count2-l` | `animation-iteration-count: 2;` |
| `.a-count3-l` | `animation-iteration-count: 5;` |
| `.a-count4-l` | `animation-iteration-count: 10;` |
| `.a-count5-l` | `animation-iteration-count: infinite;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.a-count0-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/animation-iteration-count.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/animation-iteration-count.css` — formatted
- `dist/animation-iteration-count.min.css` — minified

## License

MIT
