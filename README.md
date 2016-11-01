# css-flex-shrink 1.0.6

Css module of single purpose classes for flex shrink

#### Stats

240 | 20 | 40
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-flex-shrink
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-flex-shrink
```

ssh:
```
git clone git@github.com:tachyons-css/css-flex-shrink.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-flex-shrink";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-flex-shrink@1.0.6/css/css-flex-shrink.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-flex-shrink">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   FLEX SHRINK
*/
.fls-1 { -ms-flex-negative: 1; flex-shrink: 1; }
.fls-2 { -ms-flex-negative: 2; flex-shrink: 2; }
.fls-3 { -ms-flex-negative: 3; flex-shrink: 3; }
.fls-4 { -ms-flex-negative: 4; flex-shrink: 4; }
.fls-i { -ms-flex-negative: inherit; flex-shrink: inherit; }
@media screen and (min-width: 48em) {
 .fls-1-ns { -ms-flex-negative: 1; flex-shrink: 1; }
 .fls-2-ns { -ms-flex-negative: 2; flex-shrink: 2; }
 .fls-3-ns { -ms-flex-negative: 3; flex-shrink: 3; }
 .fls-4-ns { -ms-flex-negative: 4; flex-shrink: 4; }
 .fls-i-ns { -ms-flex-negative: inherit; flex-shrink: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .fls-1-m { -ms-flex-negative: 1; flex-shrink: 1; }
 .fls-2-m { -ms-flex-negative: 2; flex-shrink: 2; }
 .fls-3-m { -ms-flex-negative: 3; flex-shrink: 3; }
 .fls-4-m { -ms-flex-negative: 4; flex-shrink: 4; }
 .fls-i-m { -ms-flex-negative: inherit; flex-shrink: inherit; }
}
@media screen and (min-width: 64em) {
 .fls-1-l { -ms-flex-negative: 1; flex-shrink: 1; }
 .fls-2-l { -ms-flex-negative: 2; flex-shrink: 2; }
 .fls-3-l { -ms-flex-negative: 3; flex-shrink: 3; }
 .fls-4-l { -ms-flex-negative: 4; flex-shrink: 4; }
 .fls-i-l { -ms-flex-negative: inherit; flex-shrink: inherit; }
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

ISC

