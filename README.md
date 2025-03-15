# oxlint-config-egg

[![NPM version][npm-image]][npm-url]
[![build status][ci-image]][ci-url]
[![npm download][download-image]][download-url]
[![Node.js Version](https://img.shields.io/node/v/oxlint-config-egg.svg?style=flat)](https://nodejs.org/en/download/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com)
![CodeRabbit Pull Request Reviews](https://img.shields.io/coderabbit/prs/github/eggjs/oxlint-config-egg)

[npm-image]: https://img.shields.io/npm/v/oxlint-config-egg.svg?style=flat-square
[npm-url]: https://npmjs.org/package/oxlint-config-egg
[ci-image]: https://github.com/eggjs/oxlint-config-egg/actions/workflows/nodejs.yml/badge.svg
[ci-url]: https://github.com/eggjs/oxlint-config-egg/actions/workflows/nodejs.yml
[download-image]: https://img.shields.io/npm/dm/oxlint-config-egg.svg?style=flat-square
[download-url]: https://npmjs.org/package/oxlint-config-egg

Node.js Style Guide for EggJS, base on [oxlint](https://oxc.rs/docs/guide/usage/linter.html)

## Install

```bash
npm i -D oxlint oxlint-config-egg
```

## Usage

- `package.json`

```json
{
  "devDependencies": {
    "oxlint-config-egg": "1",
    "oxlint": "latest"
  }
}
```

- `.oxlintrc.json`

```json
{
  "extends": [
    "./node_modules/oxlint-config-egg/index.json"
  ]
}
```

- `package.json#scripts`

```json
{
  "scripts": {
    "lint": "oxlint",
    "lint:fix": "oxlint --fix"
  }
}
```

## License

[MIT](LICENSE)

## Contributors

[![Contributors](https://contrib.rocks/image?repo=eggjs/oxlint-config-egg)](https://github.com/eggjs/oxlint-config-egg/graphs/contributors)

Made with [contributors-img](https://contrib.rocks).
