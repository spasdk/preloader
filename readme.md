Web resources loader/cacher
===========================

[![NPM version](https://img.shields.io/npm/v/spa-preloader.svg?style=flat-square)](https://www.npmjs.com/package/spa-preloader)
[![Dependencies Status](https://img.shields.io/david/spasdk/preloader.svg?style=flat-square)](https://david-dm.org/spasdk/preloader)
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

If you have any problem or suggestion please open an issue [here](https://github.com/spasdk/preloader/issues).
Pull requests are welcomed with respect to the [JavaScript Code Style](https://github.com/DarkPark/jscs).


## License ##

`spa-preloader` is released under the [GPL-3.0 License](http://opensource.org/licenses/GPL-3.0).
