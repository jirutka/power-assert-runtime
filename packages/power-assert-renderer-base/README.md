[![power-assert][power-assert-banner]][power-assert-url]

[![Build Status][actions-ci-image]][actions-ci-url]
[![NPM version][npm-image]][npm-url]
[![License][license-image]][license-url]


Provides base class of various power-assert-renderers.


API
---------------------------------------

Override these methods as necessary.

### BaseRenderer.prototype.onStart = function (powerAssertContext) {}

Called once when traversal starts. Argument is the `powerAssertContext` object under traversal.

### BaseRenderer.prototype.onData = function (esNode) {}

Called for each Node of AST in `powerAssertContext`. Argument is a `EsNode` object.

### BaseRenderer.prototype.onEnd = function () {}

Called once when traversal ends.


INSTALL
---------------------------------------

```sh
$ npm install --save-dev power-assert-renderer-base
```


AUTHOR
---------------------------------------
* [Takuto Wada](https://github.com/twada)


LICENSE
---------------------------------------
Licensed under the [MIT](https://github.com/twada/power-assert-runtime/blob/master/LICENSE) license.


[power-assert-url]: https://github.com/power-assert-js/power-assert
[power-assert-banner]: https://raw.githubusercontent.com/power-assert-js/power-assert-js-logo/master/banner/banner-official-fullcolor.png

[actions-ci-url]: https://github.com/twada/power-assert-runtime/actions?query=workflow%3A%22CI%22
[actions-ci-image]: https://github.com/twada/power-assert-runtime/workflows/CI/badge.svg

[npm-url]: https://npmjs.org/package/power-assert-renderer-base
[npm-image]: https://badge.fury.io/js/power-assert-renderer-base.svg

[license-url]: https://github.com/twada/power-assert-runtime/blob/master/LICENSE
[license-image]: https://img.shields.io/badge/license-MIT-brightgreen.svg
