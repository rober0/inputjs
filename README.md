# InputJS
Javascript Input Mask

[![npm version](https://badge.fury.io/js/imask.svg)](https://badge.fury.io/js/imask)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Coverage Status](https://coveralls.io/repos/github/uNmAnNeR/imaskjs/badge.svg?branch=master)](https://coveralls.io/github/uNmAnNeR/imaskjs?branch=master)

## Features
* get and set *raw* and *unmasked* values easily
* no external dependencies
* supports *[overwrite](https://imask.js.org/guide.html#overwrite)* mode
* supports *web components*
* supports *contenteditable*
* **[RegExp](https://imask.js.org/guide.html#masked-base)** mask
* **[Function](https://imask.js.org/guide.html#masked-function)** mask
* **[Number](https://imask.js.org/guide.html#masked-number)** mask (integer and decimal)
* **[Date](https://imask.js.org/guide.html#masked-date)** mask (various format support, *autofix* mode)
* **[Dynamic/on-the-fly](https://imask.js.org/guide.html#masked-dynamic)** mask
* **[Pattern](https://imask.js.org/guide.html#masked-pattern)** mask
  - show placeholder always and only when necessary
  - unmasked value can contain fixed parts
  - optional input parts (greedy)
  - custom definitions
  - reusable blocks
  - secure text entry
  - **[Enum](https://imask.js.org/guide.html#masked-enum)** and **[Range](https://imask.js.org/guide.html#masked-range)** masks
  - **[Repeating](https://imask.js.org/guide.html#repeat)** blocks
* convert and format values with **[pipe](https://imask.js.org/guide.html#pipe)**

## Plugins
* [Vue plugin](https://github.com/uNmAnNeR/imaskjs/tree/master/packages/vue-imask)
* [Angular plugin](https://github.com/uNmAnNeR/imaskjs/tree/master/packages/angular-imask)
* [React plugin](https://github.com/uNmAnNeR/imaskjs/tree/master/packages/react-imask)
* [React Native plugin](https://github.com/uNmAnNeR/imaskjs/tree/master/packages/react-native-imask)
* [Svelte plugin](https://github.com/uNmAnNeR/imaskjs/tree/master/packages/svelte-imask)
* [Solid plugin](https://github.com/uNmAnNeR/imaskjs/tree/master/packages/solid-imask)

## Install
`npm install imask` and `import IMask from 'imask';`

or use CDN:

`<script src="https://unpkg.com/imask"></script>`

## Build & Test
`npm run make`

## Compatibility
Supports all major browsers. Can also be used with outdated browsers. [See how](https://imask.js.org/guide.html#support-outdated)
