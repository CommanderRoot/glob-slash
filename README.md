# glob-slash

Prefix globs with a slash and normalize. Supports negated globs too.

## Install

```
npm install glob-slash --save
```

## Usage

```js
var globSlash = require('glob-slash');

console.log(globSlash('!**/testing')) // OUTPUTS: !/**/testing
```

## Run Tests

```
npm install
npm test
```
