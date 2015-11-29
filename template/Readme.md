
# {{basename}}

[![Build status][travis-image]][travis-url]
[![Git tag][git-image]][git-url]{{#npm}}
[![NPM version][npm-image]][npm-url]{{/npm}}
[![Code style][standard-image]][standard-url]

{{description}}

## Installation

    $ npm install {{#isnt npm}}micro-js/{{/isnt}}{{basename}}

## Usage

```js
var {{camelcase basename}} = require('{{basename}}')

```

## Api

### {{camelcase basename}}(arg1, arg2)

- `arg1` -
- `arg2` -

**Returns:**

## License

MIT

[travis-image]: https://img.shields.io/travis/micro-js/{{basename}}.svg?style=flat-square
[travis-url]: https://travis-ci.org/micro-js/{{basename}}
[git-image]: https://img.shields.io/github/tag/micro-js/{{basename}}.svg
[git-url]: https://github.com/micro-js/{{basename}}
[standard-image]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat
[standard-url]: https://github.com/feross/standard{{#npm}}
[npm-image]: https://img.shields.io/npm/v/{{basename}}.svg?style=flat-square
[npm-url]: https://npmjs.org/package/{{basename}}{{/npm}}
