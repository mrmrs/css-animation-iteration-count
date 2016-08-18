# css-animation-iteration-count 0.0.7

Css module of single purpose classes for animation iteration count

#### Stats

268 | 28 | 28
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-animation-iteration-count
```

#### With Git

```
git clone https://github.com/tachyons-css/css-animation-iteration-count
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-animation-iteration-count";
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
<link rel="stylesheet" href="path/to/module/css/css-animation-iteration-count">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   ANIMATION ITERATION COUNT
*/
.a-cnt0 { animation-iteration-count: 0; }
.a-cnt1 { animation-iteration-count: 1; }
.a-cnt2 { animation-iteration-count: 2; }
.a-cnt3 { animation-iteration-count: 4; }
.a-cnt3 { animation-iteration-count: 5; }
.a-cnt4 { animation-iteration-count: 10; }
.a-cnt-inf { animation-iteration-count: infinite; }
@media screen and (min-width: 48em) {
 .a-cnt0-ns { animation-iteration-count: 0; }
 .a-cnt1-ns { animation-iteration-count: 1; }
 .a-cnt2-ns { animation-iteration-count: 2; }
 .a-cnt3-ns { animation-iteration-count: 4; }
 .a-cnt3-ns { animation-iteration-count: 5; }
 .a-cnt4-ns { animation-iteration-count: 10; }
 .a-cnt-inf-ns { animation-iteration-count: infinite; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .a-cnt0-m { animation-iteration-count: 0; }
 .a-cnt1-m { animation-iteration-count: 1; }
 .a-cnt2-m { animation-iteration-count: 2; }
 .a-cnt3-m { animation-iteration-count: 4; }
 .a-cnt3-m { animation-iteration-count: 5; }
 .a-cnt4-m { animation-iteration-count: 10; }
 .a-cnt-inf-m { animation-iteration-count: infinite; }
}
@media screen and (min-width: 64em) {
 .a-cnt0-l { animation-iteration-count: 0; }
 .a-cnt1-l { animation-iteration-count: 1; }
 .a-cnt2-l { animation-iteration-count: 2; }
 .a-cnt3-l { animation-iteration-count: 4; }
 .a-cnt3-l { animation-iteration-count: 5; }
 .a-cnt4-l { animation-iteration-count: 10; }
 .a-cnt-inf-l { animation-iteration-count: infinite; }
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
