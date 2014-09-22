# CSS TRANSITION DELAY

  Mobile-first classes for css-transition-delay.
  Set the desired css-transition-delay on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-transition-delay
```
View on [npm](https://www.npmjs.org/package/css-transition-delay)


## File Size

1.5K transition-delay.css
1.1K transition-delay.min.css

## The Code
```
.tdl0 { transition-delay: 0; }
.tdl1 { transition-delay: 1s; }
.tdl2 { transition-delay: 2s; }
.tdl3 { transition-delay: 3s; }
.tdl4 { transition-delay: 4s; }
.tdl5 { transition-delay: 8s; }
.tdl6 { transition-delay: 16s; }
.tdl7 { transition-delay: 32s; }

.tdl-i { transition-delay: initial; }

@media screen and (min-width: 48em) {
  .tdl0-ns  { transition-delay: 0; }
  .tdl1-ns  { transition-delay: 1s; }
  .tdl2-ns  { transition-delay: 2s; }
  .tdl3-ns  { transition-delay: 3s; }
  .tdl4-ns  { transition-delay: 4s; }
  .tdl5-ns  { transition-delay: 8s; }
  .tdl6-ns  { transition-delay: 16s; }
  .tdl7-ns  { transition-delay: 32s; }
  .tdl-i-ns { transition-delay: initial; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .tdl0-m  { transition-delay: 0; }
  .tdl1-m  { transition-delay: 1s; }
  .tdl2-m  { transition-delay: 2s; }
  .tdl3-m  { transition-delay: 3s; }
  .tdl4-m  { transition-delay: 4s; }
  .tdl5-m  { transition-delay: 8s; }
  .tdl6-m  { transition-delay: 16s; }
  .tdl7-m  { transition-delay: 32s; }
  .tdl-i-m { transition-delay: initial; }
}

@media screen and (min-width: 64em)  {
  .tdl0-l  { transition-delay: 0; }
  .tdl1-l  { transition-delay: 1s; }
  .tdl2-l  { transition-delay: 2s; }
  .tdl3-l  { transition-delay: 3s; }
  .tdl4-l  { transition-delay: 4s; }
  .tdl5-l  { transition-delay: 8s; }
  .tdl6-l  { transition-delay: 16s; }
  .tdl7-l  { transition-delay: 32s; }
  .tdl-i-l { transition-delay: initial; }
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

