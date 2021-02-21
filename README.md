# tsconfig

This package provides common TypeScript configurations.

## Usage

First, install this package via:

```bash
npm install @infokin/tsconfig --save-dev
```

This will install the latest version of this package from the default NPM package registry.
Use `@infokin/tsconfig@<version>` to install a specific version.

Or use:

```bash
npm install git://github.com/infokin/tsconfig --save-dev
```

This will install this package directly from the `master` branch on GitHub.

After the installation, extend from the configurations provided by this package in your project's `tsconfig.json` file
like this:

```json
{
  "extends": "@infokin/tsconfig"
}
```

Use the Angular specific TypeScript configuration in your `tsconfig.json` like this:

```json
{
  "extends": "@infokin/tsconfig/angular"
}
```

## Additional information

For more information on the TypeScript configuration see: [TSConfig Reference](https://www.typescriptlang.org/tsconfig)

For more information on the Angular specific configuration
see: [Template type checking](https://angular.io/guide/template-typecheck)
and [Angular compiler options](https://angular.io/guide/angular-compiler-options)

## Bugs & Issues

Something is not working as intended? Please report bugs or issues on
the [corresponding GitHub page](https://github.com/infokin/tsconfig/issues).

## Author

Johannes Hillert ([GitHub](https://github.com/clovergaze))

## License

Copyright (c) 2021 Johannes Hillert. Licensed under the MIT license, see the included LICENSE file for details.
