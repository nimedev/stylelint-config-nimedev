# stylelint-config-nimedev
[![npm][npm-image]][npm-url]

[npm-image]: https://img.shields.io/npm/v/stylelint-config-nimedev.svg
[npm-url]: https://npmjs.org/package/stylelint-config-nimedev

> An stylelint [Shareable Config](http://stylelint.io/user-guide/configuration/) for nimedev style rules

## Installation

```console
$ npm install stylelint-config-nimedev
```

## Usage

Set your stylelint config to:

```json
{
  "extends": "stylelint-config-nimedev"
}
```

### Extending the config

Simply add a `"rules"` key to your config and add your overrides there.

For example, to change the `indentation` to tabs:


```json
{
  "extends": "nimedev",
  "rules": {
    "indentation": "tab"
  }
}
```

## [Changelog](CHANGELOG.md)

## [License](LICENSE.md)