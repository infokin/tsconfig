# tsconfig

This package provides a common TypeScript configuration.

## Usage

First, install this package via:

```bash
npm install git://github.com/infokin/tsconfig.git#<version, e.g. 0.1.0>
```

Then extend from this package in your projects `tsconfig.json` like this:

```
{
  "extends": "@infokin/tsconfig",
  "compilerOptions": {
    "outDir": ...
  }
}
```

## Bugs & Issues
Something is not working as intended? Please feel free to report any bugs or issues using
the [corresponding GitHub page](https://github.com/infokin/tsconfig/issues).

## Author
Johannes Hillert ([GitHub](https://github.com/clovergaze))

## License
Copyright (c) 2021 Johannes Hillert. Licensed under the MIT license, see the included LICENSE file for details.
