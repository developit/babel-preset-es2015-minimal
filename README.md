# babel-preset-es2015-minimal

[![npm](https://img.shields.io/npm/v/babel-preset-es2015-minimal.svg)](http://npm.im/babel-preset-es2015-minimal)
[![travis](https://travis-ci.org/developit/babel-preset-es2015-minimal.svg?branch=master)](https://travis-ci.org/developit/babel-preset-es2015-minimal)

> Babel es2015 preset in loose mode without frills.
>
> Automatically kept in sync with `babel-preset-es2015` via [modify-babel-preset](https://github.com/developit/modify-babel-preset).


## Installation

```sh
$ npm i -S babel-preset-es2015-minimal
```


## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-minimal"]
}
```

### Via CLI

```sh
$ babel script.js --presets es2015-minimal
```

### Via Node API

```javascript
require('babel-core').transform('code', {
  presets: ['es2015-minimal']
});
```
