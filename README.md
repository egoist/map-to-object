# map-to-object

[![NPM version](https://img.shields.io/npm/v/map-to-object.svg?style=flat)](https://npmjs.com/package/map-to-object) [![NPM downloads](https://img.shields.io/npm/dm/map-to-object.svg?style=flat)](https://npmjs.com/package/map-to-object) [![Build Status](https://img.shields.io/circleci/project/egoist/map-to-object/master.svg?style=flat)](https://circleci.com/gh/egoist/map-to-object) [![donate](https://img.shields.io/badge/$-donate-ff69b4.svg?maxAge=2592000&style=flat)](https://github.com/egoist/donate)

## Install

```bash
yarn add map-to-object
```

## Usage

```js
const mapToObject = require('map-to-object')

const map = new Map()
map.set('foo', '123')

mapToObject(map)
//=> 
{
  foo: '123'
}
```

**Note**: Don't use `object` as `key` when calling `map.set`, otherwise you will get `[object Object]` in result object.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## Author

**map-to-object** © [egoist](https://github.com/egoist), Released under the [MIT](./LICENSE) License.<br>
Authored and maintained by egoist with help from contributors ([list](https://github.com/egoist/map-to-object/contributors)).

> [egoistian.com](https://egoistian.com) · GitHub [@egoist](https://github.com/egoist) · Twitter [@rem_rin_rin](https://twitter.com/rem_rin_rin)
