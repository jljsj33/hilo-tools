# hilo-tools

offline tools for react component

[![NPM version][npm-image]][npm-url]
[![gemnasium deps][gemnasium-image]][gemnasium-url]
[![node version][node-image]][node-url]
[![npm download][download-image]][download-url]

[npm-image]: http://img.shields.io/npm/v/hilo-tools.svg?style=flat-square
[npm-url]: http://npmjs.org/package/hilo-tools
[travis-image]: https://img.shields.io/travis/jljsj33/hilo-tools.svg?style=flat-square
[travis-url]: https://travis-ci.org/jljsj33/hilo-tools
[coveralls-image]: https://img.shields.io/coveralls/jljsj33/hilo-tools.svg?style=flat-square
[coveralls-url]: https://coveralls.io/r/jljsj33/hilotools?branch=master
[gemnasium-image]: http://img.shields.io/gemnasium/jljsj33/hilo-tools.svg?style=flat-square
[gemnasium-url]: https://gemnasium.com/jljsj33/hilo-tools
[node-image]: https://img.shields.io/badge/node.js-%3E=_0.11-green.svg?style=flat-square
[node-url]: http://nodejs.org/download/
[download-image]: https://img.shields.io/npm/dm/hilo-tools.svg?style=flat-square
[download-url]: https://npmjs.org/package/hilo-tools

## Usage

```
$ hilo-tools run lint: run lint by https://github.com/airbnb/javascript
$ hilo-tools run pub: compile and npm publish
$ hilo-tools run watch --out-dir=/xx: watch and compile to /xx, default to lib
$ hilo-tools run build: build examples
$ hilo-tools run gh-pages: push example to gh-pages
$ hilo-tools run start: start dev server
```


package.json demo

```js
({
  config: {
    entry:{}, // webpack entry for build dist umd
    port: 8000, // dev server port
    output:{}, // webpack output for build dist umd
  }
})
```

## History

### 6.0.0

- move test to rc-test
