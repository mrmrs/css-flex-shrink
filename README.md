# css-flex-shrink

Functional CSS for flex-shrink

## Filesize

| File | Size |
|------|------|
| `dist/flex-shrink.css` | 1381 bytes |
| `dist/flex-shrink.min.css` | 989 bytes (197 Gzipped) |

## Install

```sh
npm install css-flex-shrink
```

## Usage

### Import

```css
@import "css-flex-shrink";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-flex-shrink/dist/flex-shrink.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-flex-shrink/dist/flex-shrink.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.flex-shrink1` | `flex-shrink: .25;` |
| `.flex-shrink2` | `flex-shrink: .5;` |
| `.flex-shrink3` | `flex-shrink: 1;` |
| `.flex-shrink4` | `flex-shrink: 2;` |
| `.flex-shrink5` | `flex-shrink: 3;` |
| `.flex-shrink6` | `flex-shrink: 4;` |
| `.flex-shrink-inherit` | `flex-shrink: inherit;` |
| `.flex-shrink1-s` | `flex-shrink: .25;` |
| `.flex-shrink2-s` | `flex-shrink: .5;` |
| `.flex-shrink3-s` | `flex-shrink: 1;` |
| `.flex-shrink4-s` | `flex-shrink: 2;` |
| `.flex-shrink5-s` | `flex-shrink: 3;` |
| `.flex-shrink6-s` | `flex-shrink: 4;` |
| `.flex-shrink-inherit-s` | `flex-shrink: inherit;` |
| `.flex-shrink1-m` | `flex-shrink: .25;` |
| `.flex-shrink2-m` | `flex-shrink: .5;` |
| `.flex-shrink3-m` | `flex-shrink: 1;` |
| `.flex-shrink4-m` | `flex-shrink: 2;` |
| `.flex-shrink5-m` | `flex-shrink: 3;` |
| `.flex-shrink6-m` | `flex-shrink: 4;` |
| `.flex-shrink-inherit-m` | `flex-shrink: inherit;` |
| `.flex-shrink1-l` | `flex-shrink: .25;` |
| `.flex-shrink2-l` | `flex-shrink: .5;` |
| `.flex-shrink3-l` | `flex-shrink: 1;` |
| `.flex-shrink4-l` | `flex-shrink: 2;` |
| `.flex-shrink5-l` | `flex-shrink: 3;` |
| `.flex-shrink6-l` | `flex-shrink: 4;` |
| `.flex-shrink-inherit-l` | `flex-shrink: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.flex-shrink1-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/flex-shrink.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/flex-shrink.css` — formatted
- `dist/flex-shrink.min.css` — minified

## License

MIT
