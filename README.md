# @jldensmore/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@bamblehorse/tiny.svg)](https://www.npmjs.com/package/@jldensmore/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@bamblehorse/tiny.svg)](https://www.npmjs.com/package/@jldensmore/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @jldensmore/tiny -s
```

## Usage

```js
const tiny = require("@jldensmore/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
