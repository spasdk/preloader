Web resources loader/cacher
===========================

[![build status](https://img.shields.io/travis/spasdk/preloader.svg?style=flat-square)](https://travis-ci.org/spasdk/preloader)
[![npm version](https://img.shields.io/npm/v/spa-preloader.svg?style=flat-square)](https://www.npmjs.com/package/spa-preloader)
[![dependencies status](https://img.shields.io/david/spasdk/preloader.svg?style=flat-square)](https://david-dm.org/spasdk/preloader)
[![devDependencies status](https://img.shields.io/david/dev/spasdk/preloader.svg?style=flat-square)](https://david-dm.org/spasdk/preloader?type=dev)
[![Gitter](https://img.shields.io/badge/gitter-join%20chat-blue.svg?style=flat-square)](https://gitter.im/DarkPark/spasdk)


This cacher module is an instance of [Emitter](https://github.com/cjssdk/emitter) module.
Loads images and other web resources to have instant access in the future.


## Installation ##

```bash
npm install spa-preloader
```


## Usage ##

Add to the scope:

```js
var preloader = require('spa-preloader');
```


## Development mode ##

> There is a global var `DEVELOP` which activates additional consistency checks and protection logic not available in release mode.


## Contribution ##

If you have any problems or suggestions please open an [issue](https://github.com/spasdk/preloader/issues)
according to the contribution [rules](.github/contributing.md).


## License ##

`spa-preloader` is released under the [MIT License](license.md).
