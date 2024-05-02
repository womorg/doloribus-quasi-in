# @womorg/doloribus-quasi-in <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple list of possible Typed Array names.

## Example

```js
const assert = require('assert');

const names = require('@womorg/doloribus-quasi-in');

assert(Array.isArray(names));
assert(names.every(name => (
    typeof name === 'string'
    && typeof globalThis[name] === 'function'
    && globalThis[name].name === name
)));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@womorg/doloribus-quasi-in
[npm-version-svg]: https://versionbadg.es/ljharb/@womorg/doloribus-quasi-in.svg
[deps-svg]: https://david-dm.org/ljharb/@womorg/doloribus-quasi-in.svg
[deps-url]: https://david-dm.org/ljharb/@womorg/doloribus-quasi-in
[dev-deps-svg]: https://david-dm.org/ljharb/@womorg/doloribus-quasi-in/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@womorg/doloribus-quasi-in#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@womorg/doloribus-quasi-in.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@womorg/doloribus-quasi-in.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@womorg/doloribus-quasi-in.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@womorg/doloribus-quasi-in
[codecov-image]: https://codecov.io/gh/ljharb/@womorg/doloribus-quasi-in/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@womorg/doloribus-quasi-in/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@womorg/doloribus-quasi-in
[actions-url]: https://github.com/womorg/doloribus-quasi-in/actions
