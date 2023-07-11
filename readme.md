# @followdev/notes-library

[![npm (scoped)](https://img.shields.io/npm/v/@followdev/notes-library.svg)](https://www.npmjs.com/package/@followdev/notes-library)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@followdev/notes-library.svg)](https://www.npmjs.com/package/@followdev/notes-library)

Removes all spaces from a string.

## Install

```
$ npm install @followdev/notes-library
```

## Usage

```js
const tiny = require("@followdev/notes-library");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```