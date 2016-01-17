# module resolves
Checks to see if a node module (or custom module) exists -- WITHOUT requiring it. If it exists, do stuff, if not, return false.

## Installation
```
npm install module-resolves --save
```

## Basic Usage
```js
var module_resolves = require('module-resolves');

if (module_resolves('./your-directory/your-module.js')) {
   var your-module = require('./your-directory/your-module.js);
}
```


Inspired by [Tobias Oberrauch](https://github.com/tobiasoberrauch/module-exists)