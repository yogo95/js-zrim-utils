# JavaScript Zrim Utils

## Introduction

Contains node.js utility functions

## JavaScript Helper

### Extract function name

You can extract a function name from 2 ways:
- A function : *extractFunctionName*
- An instance : *extractFunctionNameFromInstance*


Examples:
````javascript

const javaScriptHelper = require('js-zrim-utils').javaScriptHelper;

function myFunctionName() {
  
}

javaScriptHelper.extractFunctionName(myFunctionName); // myFunctionName
````

````javascript
const javaScriptHelper = require('js-zrim-utils').javaScriptHelper;
function MyClassName() {
  
}

const instance = new MyClassName();
javaScriptHelper.extractFunctionNameFromInstance(instance); // MyClassName
````
