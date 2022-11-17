# Basic math methods

![travis test](https://travis-ci.com/sillyangel/math.svg?branch=main) [![GitHub issues](https://img.shields.io/github/issues/sillyangel/math)](https://github.com/sillyangel/math/issues) ![GitHub last commit](https://img.shields.io/github/last-commit/sillyangel/math) ![npm](https://img.shields.io/npm/v/@sillyangel/math) ![NPM](https://img.shields.io/npm/l/@sillyangel/math)

## How to install

```bash
npm install @sillyangel/math
```

## How to use

```js
// require
const basicMaths = require("@sillyangel/math");
```

Or you can add to your `package.json` the property `"type": "module",` and use instead

```js
// import
import basicMaths from '@sillyangel/math';
```

```js
// methods
const add = basicMaths.add(1, 3); // return 4

const substract = basicMaths.substract(1, 2); // return -1

const multiply = basicMaths.multiply(1, 2); // return 2

const divideGood = basicMaths.divide(1, 2); // Good - return 0.5

const divideBad = basicMaths.divide(1, 0); // Bad - No number is divisible by zero

const powOperation = basicMaths.powOperation(2, 2); // return 8
```

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/sillyangel/math) ![npm](https://img.shields.io/npm/dt/@sillyangel/math) [![GitHub forks](https://img.shields.io/github/forks/sillyangel/math)](https://github.com/sillyangel/math/network) [![GitHub stars](https://img.shields.io/github/stars/sillyangel/math)](https://github.com/sillyangel/math/stargazers) [![jsDelivr](https://data.jsdelivr.com/v1/package/npm/@sillyangel/math/badge?style=rounded)](https://www.jsdelivr.com/package/npm/@sillyangel/math) ![GitHub contributors](https://img.shields.io/github/contributors/sillyangel/math?color=success) ![npm collaborators](https://img.shields.io/npm/collaborators/@sillyangel/math?color=success)

## CNDs

If your application is not from Node and you still want to use it on the frontend, you can import the CDN that is hosted on [jsDelivr](https://www.jsdelivr.com/package/npm/@sillyangel/math)

### How to import

Just copy and paste in your html this script

```html
<script src="https://cdn.jsdelivr.net/npm/@sillyangel/math@1.0.0/index.min.js"></script>
```
