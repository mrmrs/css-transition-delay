# css-transition-delay 0.0.6

Css module of single purpose classes for transition delay

#### Stats

291 | 36 | 36
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-transition-delay
```

#### With Git

```
git clone https://github.com/tachyons-css/css-transition-delay
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-transition-delay";
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
<link rel="stylesheet" href="path/to/module/css/css-transition-delay">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   TRANSITION DELAY
*/
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
 .tdl0-ns { transition-delay: 0; }
 .tdl1-ns { transition-delay: 1s; }
 .tdl2-ns { transition-delay: 2s; }
 .tdl3-ns { transition-delay: 3s; }
 .tdl4-ns { transition-delay: 4s; }
 .tdl5-ns { transition-delay: 8s; }
 .tdl6-ns { transition-delay: 16s; }
 .tdl7-ns { transition-delay: 32s; }
 .tdl-i-ns { transition-delay: initial; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .tdl0-m { transition-delay: 0; }
 .tdl1-m { transition-delay: 1s; }
 .tdl2-m { transition-delay: 2s; }
 .tdl3-m { transition-delay: 3s; }
 .tdl4-m { transition-delay: 4s; }
 .tdl5-m { transition-delay: 8s; }
 .tdl6-m { transition-delay: 16s; }
 .tdl7-m { transition-delay: 32s; }
 .tdl-i-m { transition-delay: initial; }
}
@media screen and (min-width: 64em) {
 .tdl0-l { transition-delay: 0; }
 .tdl1-l { transition-delay: 1s; }
 .tdl2-l { transition-delay: 2s; }
 .tdl3-l { transition-delay: 3s; }
 .tdl4-l { transition-delay: 4s; }
 .tdl5-l { transition-delay: 8s; }
 .tdl6-l { transition-delay: 16s; }
 .tdl7-l { transition-delay: 32s; }
 .tdl-i-l { transition-delay: initial; }
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

