# @vicnala/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@vicnala/tiny.svg)](https://www.npmjs.com/package/@vicnala/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@vicnala/tiny.svg)](https://www.npmjs.com/package/@vicnala/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @vicnala/tiny
```

## Usage

```js
const tiny = require("@vicnala/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
