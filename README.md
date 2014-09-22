# CSS ANIMATION ITERATION COUNT

  Mobile-first classes for css-animation-iteration-count.
  Set the desired css-animation-iteration-count on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-animation-iteration-count
```
View on [npm](https://www.npmjs.org/package/css-animation-iteration-count)


## File Size

1.5K animation-iteration-count.css
1.2K animation-iteration-count.min.css 
221B minified and gzipped

## The Code
```
  .a-cnt0    { animation-iteration-count: 0; }
  .a-cnt1    { animation-iteration-count: 1; }
  .a-cnt2    { animation-iteration-count: 2; }
  .a-cnt3    { animation-iteration-count: 4; }
  .a-cnt3    { animation-iteration-count: 5; }
  .a-cnt4    { animation-iteration-count: 10; }
  .a-cnt-inf { animation-iteration-count: infinite; }

@media screen and (min-width: 48em) {
  .a-cnt0-ns    { animation-iteration-count: 0; }
  .a-cnt1-ns    { animation-iteration-count: 1; }
  .a-cnt2-ns    { animation-iteration-count: 2; }
  .a-cnt3-ns    { animation-iteration-count: 4; }
  .a-cnt3-ns    { animation-iteration-count: 5; }
  .a-cnt4-ns    { animation-iteration-count: 10; }
  .a-cnt-inf-ns { animation-iteration-count: infinite; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .a-cnt0-m    { animation-iteration-count: 0; }
  .a-cnt1-m    { animation-iteration-count: 1; }
  .a-cnt2-m    { animation-iteration-count: 2; }
  .a-cnt3-m    { animation-iteration-count: 4; }
  .a-cnt3-m    { animation-iteration-count: 5; }
  .a-cnt4-m    { animation-iteration-count: 10; }
  .a-cnt-inf-m { animation-iteration-count: infinite; }
}

@media screen and (min-width: 64em)  {
  .a-cnt0-l    { animation-iteration-count: 0; }
  .a-cnt1-l    { animation-iteration-count: 1; }
  .a-cnt2-l    { animation-iteration-count: 2; }
  .a-cnt3-l    { animation-iteration-count: 4; }
  .a-cnt3-l    { animation-iteration-count: 5; }
  .a-cnt4-l    { animation-iteration-count: 10; }
  .a-cnt-inf-l { animation-iteration-count: infinite; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

