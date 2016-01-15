# css-flex-shrink 0.0.7

Css module of single purpose classes for flex shrink

#### Stats

208 | 20 | 20
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-flex-shrink
```

#### With Git

```
git clone https://github.com/tachyons-css/css-flex-shrink
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-flex-shrink";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-flex-shrink">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   FLEX SHRINK
*/
.fls-1 { flex-shrink: 1; }
.fls-2 { flex-shrink: 2; }
.fls-3 { flex-shrink: 3; }
.fls-4 { flex-shrink: 4; }
.fls-i { flex-shrink: inherit; }
@media screen and (min-width: 48em) {
 .fls-1-ns { flex-shrink: 1; }
 .fls-2-ns { flex-shrink: 2; }
 .fls-3-ns { flex-shrink: 3; }
 .fls-4-ns { flex-shrink: 4; }
 .fls-i-ns { flex-shrink: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .fls-1-m { flex-shrink: 1; }
 .fls-2-m { flex-shrink: 2; }
 .fls-3-m { flex-shrink: 3; }
 .fls-4-m { flex-shrink: 4; }
 .fls-i-m { flex-shrink: inherit; }
}
@media screen and (min-width: 64em) {
 .fls-1-l { flex-shrink: 1; }
 .fls-2-l { flex-shrink: 2; }
 .fls-3-l { flex-shrink: 3; }
 .fls-4-l { flex-shrink: 4; }
 .fls-i-l { flex-shrink: inherit; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

