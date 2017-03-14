# Servie Finalhandler

[![NPM version][npm-image]][npm-url]
[![NPM downloads][downloads-image]][downloads-url]
[![Build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![Greenkeeper badge](https://badges.greenkeeper.io/blakeembrey/node-servie-finalhandler.svg)](https://greenkeeper.io/)

> Servie final HTTP 404 responder.

## Installation

```
npm install servie-finalhandler --save
```

## Usage

```ts
import { finalhandler } from 'servie-finalhandler'

const app = compose([get(...), post(...)])

app(new Request({ url: '/' }), finalhandler)
```

## TypeScript

This project is written using [TypeScript](https://github.com/Microsoft/TypeScript) and publishes the definitions directly to NPM.

## License

MIT

[npm-image]: https://img.shields.io/npm/v/servie-finalhandler.svg?style=flat
[npm-url]: https://npmjs.org/package/servie-finalhandler
[downloads-image]: https://img.shields.io/npm/dm/servie-finalhandler.svg?style=flat
[downloads-url]: https://npmjs.org/package/servie-finalhandler
[travis-image]: https://img.shields.io/travis/blakeembrey/node-servie-finalhandler.svg?style=flat
[travis-url]: https://travis-ci.org/blakeembrey/node-servie-finalhandler
[coveralls-image]: https://img.shields.io/coveralls/blakeembrey/node-servie-finalhandler.svg?style=flat
[coveralls-url]: https://coveralls.io/r/blakeembrey/node-servie-finalhandler?branch=master
