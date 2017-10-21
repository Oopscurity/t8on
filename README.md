# t8on &middot; [![Build Status](https://travis-ci.org/Oopscurity/t8on.svg?branch=master)](https://travis-ci.org/Oopscurity/t8on) [![Coverage Status](https://coveralls.io/repos/github/Oopscurity/t8on/badge.svg?branch=master)](https://coveralls.io/github/Oopscurity/t8on?branch=master)

`t8on` is a JavaScript library for managing sets of locales and phrases in the application.

## Usage

The paragraph is under development.

## Installation

t8on is available as the [`t8on`](https://www.npmjs.com/package/t8on) package on [npm](https://www.npmjs.com/).

To install the latest stable version, type

`npm install --save t8on`

You can also access package's files on [unpkg.com](https://unpkg.com/t8on).

The package provides a [CommonJS](https://webpack.js.org/api/module-methods/#commonjs) module in the `lib` directory and a production-ready [UMD](https://github.com/umdjs/umd) build in the `dist` folder.

Although t8on is intended for usage with module bundlers such as [Webpack](https://webpack.js.org/), thanks to UMD, it's possible to use `t8on` with many other JavaScript module loaders or completely without them.

If it sounds like your case, you can simply connect the UMD build as a `<script>` tag on the web page. After that, the library will be available via `window.t8on`.

## Licence

`t8on` is [MIT licensed](https://github.com/Oopscurity/t8on/blob/master/LICENSE).
