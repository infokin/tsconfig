# tsconfig

This package provides common TypeScript configurations.

## Usage

First, install this package via:

```bash
npm install git://github.com/infokin/tsconfig.git#<version> --save-dev
```

`version` can be a specific release version, e.g. `0.1.0`. If `version` is omitted the package is installed from the `master` branch.

After the installation, extend from this package in your projects `tsconfig.json` like this:

```json
{
  "extends": "@infokin/tsconfig"
}
```

To use the Angular specifc TypeScript configuration extend from this package like this in your `tsconfig.json`:

```json
{
  "extends": "@infokin/tsconfig/angular"
}
```

## Additional information

For more information on the TypeScript configuration see: [TSConfig Reference](https://www.typescriptlang.org/tsconfig)

For more information on the Angular specific configuration see: [Template type checking](https://angular.io/guide/template-typecheck) and [Angular compiler options](https://angular.io/guide/angular-compiler-options)

## Bugs & Issues
Something is not working as intended? Please report bugs or issues on the [corresponding GitHub page](https://github.com/infokin/tsconfig/issues).

## Author
Johannes Hillert ([GitHub](https://github.com/clovergaze))

## License
Copyright (c) 2021 Johannes Hillert. Licensed under the MIT license, see the included LICENSE file for details.
