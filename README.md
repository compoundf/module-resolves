# module resolves
Checks to see if a node module (or custom module) exists -- WITHOUT requiring it. If it exists, do stuff, if not, return false.

## Installation
```
npm install module-resolves --save
```

## Basic Usage
```js
var module_resolves = require('module-resolves');

if (module_resolves('./your-directory/yourModule.js')) {
   var yourModule = require('./your-directory/yourModule.js');
}
```


Inspired by [Tobias Oberrauch](https://github.com/tobiasoberrauch/module-exists)