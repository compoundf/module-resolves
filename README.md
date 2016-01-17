# module resolves
Checks to see if a node module (or custom module) exists -- WITHOUT requiring it. If it exists, it will return true, if not, return false. Similar modules will go ahead and require it if it exists, but this one does not. It's been helpful for me! Perhaps you can get some use out of it also :)

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