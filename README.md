# css-animation-iteration-count 1.0.6

Css module of single purpose classes for animation iteration count

#### Stats

306 | 28 | 56
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-animation-iteration-count
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-animation-iteration-count
```

ssh:
```
git clone git@github.com:tachyons-css/css-animation-iteration-count.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-animation-iteration-count";
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
<link rel="stylesheet" href="http://unpkg.com/css-animation-iteration-count@1.0.6/css/css-animation-iteration-count.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-animation-iteration-count">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   ANIMATION ITERATION COUNT
*/
.a-cnt0 { -webkit-animation-iteration-count: 0; animation-iteration-count: 0; }
.a-cnt1 { -webkit-animation-iteration-count: 1; animation-iteration-count: 1; }
.a-cnt2 { -webkit-animation-iteration-count: 2; animation-iteration-count: 2; }
.a-cnt3 { -webkit-animation-iteration-count: 4; animation-iteration-count: 4; }
.a-cnt3 { -webkit-animation-iteration-count: 5; animation-iteration-count: 5; }
.a-cnt4 { -webkit-animation-iteration-count: 10; animation-iteration-count: 10; }
.a-cnt-inf { -webkit-animation-iteration-count: infinite; animation-iteration-count: infinite; }
@media screen and (min-width: 48em) {
 .a-cnt0-ns { -webkit-animation-iteration-count: 0; animation-iteration-count: 0; }
 .a-cnt1-ns { -webkit-animation-iteration-count: 1; animation-iteration-count: 1; }
 .a-cnt2-ns { -webkit-animation-iteration-count: 2; animation-iteration-count: 2; }
 .a-cnt3-ns { -webkit-animation-iteration-count: 4; animation-iteration-count: 4; }
 .a-cnt3-ns { -webkit-animation-iteration-count: 5; animation-iteration-count: 5; }
 .a-cnt4-ns { -webkit-animation-iteration-count: 10; animation-iteration-count: 10; }
 .a-cnt-inf-ns { -webkit-animation-iteration-count: infinite; animation-iteration-count: infinite; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .a-cnt0-m { -webkit-animation-iteration-count: 0; animation-iteration-count: 0; }
 .a-cnt1-m { -webkit-animation-iteration-count: 1; animation-iteration-count: 1; }
 .a-cnt2-m { -webkit-animation-iteration-count: 2; animation-iteration-count: 2; }
 .a-cnt3-m { -webkit-animation-iteration-count: 4; animation-iteration-count: 4; }
 .a-cnt3-m { -webkit-animation-iteration-count: 5; animation-iteration-count: 5; }
 .a-cnt4-m { -webkit-animation-iteration-count: 10; animation-iteration-count: 10; }
 .a-cnt-inf-m { -webkit-animation-iteration-count: infinite; animation-iteration-count: infinite; }
}
@media screen and (min-width: 64em) {
 .a-cnt0-l { -webkit-animation-iteration-count: 0; animation-iteration-count: 0; }
 .a-cnt1-l { -webkit-animation-iteration-count: 1; animation-iteration-count: 1; }
 .a-cnt2-l { -webkit-animation-iteration-count: 2; animation-iteration-count: 2; }
 .a-cnt3-l { -webkit-animation-iteration-count: 4; animation-iteration-count: 4; }
 .a-cnt3-l { -webkit-animation-iteration-count: 5; animation-iteration-count: 5; }
 .a-cnt4-l { -webkit-animation-iteration-count: 10; animation-iteration-count: 10; }
 .a-cnt-inf-l { -webkit-animation-iteration-count: infinite; animation-iteration-count: infinite; }
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

