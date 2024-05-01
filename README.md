# @omegion1npm/repellendus-sed-aut <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@omegion1npm/repellendus-sed-aut');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@omegion1npm/repellendus-sed-aut
[npm-version-svg]: https://versionbadg.es/inspect-js/@omegion1npm/repellendus-sed-aut.svg
[deps-svg]: https://david-dm.org/inspect-js/@omegion1npm/repellendus-sed-aut.svg
[deps-url]: https://david-dm.org/inspect-js/@omegion1npm/repellendus-sed-aut
[dev-deps-svg]: https://david-dm.org/inspect-js/@omegion1npm/repellendus-sed-aut/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@omegion1npm/repellendus-sed-aut#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@omegion1npm/repellendus-sed-aut.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@omegion1npm/repellendus-sed-aut.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@omegion1npm/repellendus-sed-aut.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@omegion1npm/repellendus-sed-aut
[codecov-image]: https://codecov.io/gh/inspect-js/@omegion1npm/repellendus-sed-aut/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@omegion1npm/repellendus-sed-aut/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@omegion1npm/repellendus-sed-aut
[actions-url]: https://github.com/omegion1npm/repellendus-sed-aut/actions
