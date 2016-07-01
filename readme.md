# tachyons-borders 2.1.1

Performance-first css module for styling borders.

#### Stats

386 | 40 | 64
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-borders
```

#### With Git

```
git clone https://github.com/tachyons-css/tachyons-borders
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-borders";
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
<link rel="stylesheet" href="path/to/module/css/tachyons-borders">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*

   BORDER BASE

   Legend

   a = all
   t = top
   r = right
   b = bottom
   l = left

*/
.ba { border-style: solid; border-width: 1px; }
.bt { border-top-style: solid; border-top-width: 1px; }
.br { border-right-style: solid; border-right-width: 1px; }
.bb { border-bottom-style: solid; border-bottom-width: 1px; }
.bl { border-left-style: solid; border-left-width: 1px; }
.bn { border-style: none; border-width: 0; }
.bt-0 { border-top-width: 0; }
.br-0 { border-right-width: 0; }
.bb-0 { border-bottom-width: 0; }
.bl-0 { border-left-width: 0; }
@media screen and (min-width: 48em) {
 .ba-ns { border-style: solid; border-width: 1px; }
 .bt-ns { border-top-style: solid; border-top-width: 1px; }
 .br-ns { border-right-style: solid; border-right-width: 1px; }
 .bb-ns { border-bottom-style: solid; border-bottom-width: 1px; }
 .bl-ns { border-left-style: solid; border-left-width: 1px; }
 .bn-ns { border-style: none; border-width: 0; }
 .bt-0-ns { border-top-width: 0; }
 .br-0-ns { border-right-width: 0; }
 .bb-0-ns { border-bottom-width: 0; }
 .bl-0-ns { border-left-width: 0; }
}
@media screen and (min-width: 48em) and (max-width: 64em) {
 .ba-m { border-style: solid; border-width: 1px; }
 .bt-m { border-top-style: solid; border-top-width: 1px; }
 .br-m { border-right-style: solid; border-right-width: 1px; }
 .bb-m { border-bottom-style: solid; border-bottom-width: 1px; }
 .bl-m { border-left-style: solid; border-left-width: 1px; }
 .bn-m { border-style: none; border-width: 0; }
 .bt-0-m { border-top-width: 0; }
 .br-0-m { border-right-width: 0; }
 .bb-0-m { border-bottom-width: 0; }
 .bl-0-m { border-left-width: 0; }
}
@media screen and (min-width: 64em) {
 .ba-l { border-style: solid; border-width: 1px; }
 .bt-l { border-top-style: solid; border-top-width: 1px; }
 .br-l { border-right-style: solid; border-right-width: 1px; }
 .bb-l { border-bottom-style: solid; border-bottom-width: 1px; }
 .bl-l { border-left-style: solid; border-left-width: 1px; }
 .bn-l { border-style: none; border-width: 0; }
 .bt-0-l { border-top-width: 0; }
 .br-0-l { border-right-width: 0; }
 .bb-0-l { border-bottom-width: 0; }
 .bl-0-l { border-left-width: 0; }
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

