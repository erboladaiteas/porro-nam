# @erboladaiteas/porro-nam <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @erboladaiteas/porro-nam
```

## Usage/Examples

```js
var regexTester = require('@erboladaiteas/porro-nam');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@erboladaiteas/porro-nam
[npm-version-svg]: https://versionbadg.es/ljharb/@erboladaiteas/porro-nam.svg
[deps-svg]: https://david-dm.org/ljharb/@erboladaiteas/porro-nam.svg
[deps-url]: https://david-dm.org/ljharb/@erboladaiteas/porro-nam
[dev-deps-svg]: https://david-dm.org/ljharb/@erboladaiteas/porro-nam/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@erboladaiteas/porro-nam#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@erboladaiteas/porro-nam.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@erboladaiteas/porro-nam.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@erboladaiteas/porro-nam.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@erboladaiteas/porro-nam
[codecov-image]: https://codecov.io/gh/ljharb/@erboladaiteas/porro-nam/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@erboladaiteas/porro-nam/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@erboladaiteas/porro-nam
[actions-url]: https://github.com/erboladaiteas/porro-nam/actions
