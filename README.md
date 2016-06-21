Bitcore Library for Kobocoin
=======

[![NPM Package](https://img.shields.io/npm/v/bitcore-lib.svg?style=flat-square)](https://www.npmjs.org/package/bitcore-lib)
[![Build Status](https://img.shields.io/travis/bitpay/bitcore-lib.svg?branch=master&style=flat-square)](https://travis-ci.org/bitpay/bitcore-lib)
[![Coverage Status](https://img.shields.io/coveralls/bitpay/bitcore-lib.svg?style=flat-square)](https://coveralls.io/r/bitpay/bitcore-lib)

A pure and powerful JavaScript Kobocoin Library based on the Bitcore Library.

## Principles

Kobocoin is a powerful new peer-to-peer platform for the next generation of financial technology. The decentralized nature of the Kobocoin network allows for highly resilient Kobocoin infrastructure, and the developer community needs reliable, open-source tools to implement kobocoin apps and services.

## Documentation

This Kobocoin Library is based on The Bitpay Bitcore libraries https://github.com/bitpay/bitcore-lib

The complete docs are hosted here: [bitcore documentation](http://bitcore.io/guide/). There's also a [bitcore API reference](http://bitcore.io/api/) available generated from the JSDocs of the project, where you'll find low-level details on each bitcore utility.

- [Read the Developer Guide](http://bitcore.io/guide/)
- [Read the API Reference](http://bitcore.io/api/)


## Examples

* [Generate a random address](https://github.com/bitpay/bitcore-lib/blob/master/docs/examples.md#generate-a-random-address)
* [Generate a address from a SHA256 hash](https://github.com/bitpay/bitcore-lib/blob/master/docs/examples.md#generate-a-address-from-a-sha256-hash)
* [Import an address via WIF](https://github.com/bitpay/bitcore-lib/blob/master/docs/examples.md#import-an-address-via-wif)
* [Create a Transaction](https://github.com/bitpay/bitcore-lib/blob/master/docs/examples.md#create-a-transaction)
* [Sign a Kobocoin message](https://github.com/bitpay/bitcore-lib/blob/master/docs/examples.md#sign-a-bitcoin-message)
* [Verify a Kobocoin message](https://github.com/bitpay/bitcore-lib/blob/master/docs/examples.md#verify-a-bitcoin-message)
* [Create an OP RETURN transaction](https://github.com/bitpay/bitcore-lib/blob/master/docs/examples.md#create-an-op-return-transaction)
* [Create a 2-of-3 multisig P2SH address](https://github.com/bitpay/bitcore-lib/blob/master/docs/examples.md#create-a-2-of-3-multisig-p2sh-address)
* [Spend from a 2-of-2 multisig P2SH address](https://github.com/bitpay/bitcore-lib/blob/master/docs/examples.md#spend-from-a-2-of-2-multisig-p2sh-address)


## Security

We're using Kobocore in production, but please use common sense when doing anything related to finances! We take no responsibility for your implementation decisions.


## Building the Browser Bundle

To build a kobocore-lib full bundle for the browser:

```sh
gulp browser
```

This will generate files named `kobocore-lib.js` and `kobocore-lib.min.js`.

## Development & Tests

```sh
git clone https://github.com/kobocoin/bitcore-lib-kobo
cd bitcore-lib-kobo
npm install
```

Run all the tests:

```sh
gulp test
```

You can also run just the Node.js tests with `gulp test:node`, just the browser tests with `gulp test:browser`
or create a test coverage report (you can open `coverage/lcov-report/index.html` to visualize it) with `gulp coverage`.

## License

Code released under [the MIT license](https://github.com/kobocoin/bitcore-lib-kobo/blob/master/LICENSE).

Copyright 2015-2016 Kobocoin, The Kobocoin Developers.
