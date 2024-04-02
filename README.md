# @npmtuanmap2024/maiores-eaque-est-tempora <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@npmtuanmap2024/maiores-eaque-est-tempora');
const Eval = require('@npmtuanmap2024/maiores-eaque-est-tempora/eval');
const Range = require('@npmtuanmap2024/maiores-eaque-est-tempora/range');
const Ref = require('@npmtuanmap2024/maiores-eaque-est-tempora/ref');
const Syntax = require('@npmtuanmap2024/maiores-eaque-est-tempora/syntax');
const Type = require('@npmtuanmap2024/maiores-eaque-est-tempora/type');
const URI = require('@npmtuanmap2024/maiores-eaque-est-tempora/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@npmtuanmap2024/maiores-eaque-est-tempora
[npm-version-svg]: https://versionbadg.es/ljharb/@npmtuanmap2024/maiores-eaque-est-tempora.svg
[deps-svg]: https://david-dm.org/ljharb/@npmtuanmap2024/maiores-eaque-est-tempora.svg
[deps-url]: https://david-dm.org/ljharb/@npmtuanmap2024/maiores-eaque-est-tempora
[dev-deps-svg]: https://david-dm.org/ljharb/@npmtuanmap2024/maiores-eaque-est-tempora/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@npmtuanmap2024/maiores-eaque-est-tempora#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@npmtuanmap2024/maiores-eaque-est-tempora.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@npmtuanmap2024/maiores-eaque-est-tempora.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@npmtuanmap2024/maiores-eaque-est-tempora.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@npmtuanmap2024/maiores-eaque-est-tempora
[codecov-image]: https://codecov.io/gh/ljharb/@npmtuanmap2024/maiores-eaque-est-tempora/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@npmtuanmap2024/maiores-eaque-est-tempora/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@npmtuanmap2024/maiores-eaque-est-tempora
[actions-url]: https://github.com/npmtuanmap2024/maiores-eaque-est-tempora/actions
