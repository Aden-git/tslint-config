# @ptsecurity/tslint-config

[![Version][version-badge]][npm]

## Install

Install as an [npm][npm] devDependency. [TypeScript][typescript] and [TSLint][tslint]
should also be installed.

```sh
npm install --save-dev typescript tslint @ptsecurity/tslint-config
```

## Usage

Include a `tslint.json` file in your project and add `"@ptsecurity/tslint-config"` to
the `"extends"` field. Custom rules can then be enabled under `"rules"`.

```json
{
  "extends": ["@ptsecurity/tslint-config"],
  "rules": {
    ...
  }
}
```

[version-badge]: https://img.shields.io/npm/v/@ptsecurity/tslint-config.svg?style=flat-square
[npm]: https://www.npmjs.com/package/@ptsecurity/tslint-config
[typescript]: https://www.typescriptlang.org/
[tslint]: https://palantir.github.io/tslint/
[license]: LICENSE