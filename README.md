# npm-package-test

![](https://img.shields.io/npm/v/@mottz/tiny.svg?style=flat)
![](https://img.shields.io/bundlephobia/min/@mottz/tiny.svg?style=flat)

This repo is for education purposes.

## Install

```
$ npm install @mottz/tiny
```

## Usage

```js
const tiny = require("@mottz/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```

