# hedges [![Build Status][travis-badge]][travis] [![Coverage Status][codecov-badge]][codecov]

List of _supposed_ English (both British and American) hedge words.

## Installation

[npm][npm-install]:

```bash
npm install hedges
```

**hedges** is also available for [duo][duo-install], and as an
AMD, CommonJS, and globals module, [uncompressed and compressed][releases].

## Usage

```js
var hedges = require("hedges");

hedges.length; // 162

console.log(hedges.slice(0, 10));
```

Yields:

```json
[
  "a bit",
  "about",
  "actually",
  "allege",
  "alleged",
  "almost",
  "almost never",
  "always",
  "and all that",
  "and so forth"
]
```

## API

### `hedges`

**Type**: `Array.<string>` — _Roughly_, **hedges** exposes information
as an list of strings.

## Support

For a complete list of supported hedge words and phrases, _like_, see
[support.md][support].

Note that the words listed in **hedges** are _speculated_ to be hedges,
although _perhaps_ not.

## Related

*   [buzzwords](https://github.com/wooorm/buzzwords)
    — List of buzzwords;

*   [dale-chall](https://github.com/wooorm/dale-chall)
    — List of familiar American-English words (1995);

*   [fillers](https://github.com/wooorm/fillers)
    — List of filler words;

*   [profanities](https://github.com/wooorm/profanities)
    — List of profane words;

*   [spache](https://github.com/wooorm/spache)
    — List of simple American-English words (1974);

*   [weasels](https://github.com/wooorm/weasels)
    — List of weasel words.

## License

[MIT][license] © [Titus Wormer][author]

<!-- Definitions -->

[travis-badge]: https://img.shields.io/travis/wooorm/hedges.svg

[travis]: https://travis-ci.org/wooorm/hedges

[codecov-badge]: https://img.shields.io/codecov/c/github/wooorm/hedges.svg

[codecov]: https://codecov.io/github/wooorm/hedges

[npm-install]: https://docs.npmjs.com/cli/install

[duo-install]: http://duojs.org/#getting-started

[releases]: https://github.com/wooorm/hedges/releases

[license]: LICENSE

[support]: support.md

[author]: http://wooorm.com
