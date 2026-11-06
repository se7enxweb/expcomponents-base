# expcomponents-base

The Base package provides the basic infrastructure that all packages rely on. Therefore every component relies on this package.

This is the Exponential fork of [zetacomponents/Base](https://github.com/zetacomponents/Base),
maintained by 7x (se7en.x) and the Exponential Foundation for Exponential and anyone else
who uses the Zeta Components Base component on current PHP versions. All credit for the
component goes to the Zeta Components authors listed in `composer.json` and `CREDITS`;
the upstream copyright notices (`NOTICE`) and the Apache License 2.0 (`LICENSE.txt`)
are kept unchanged.

## What is different from upstream

- The package is `se7enxweb/expcomponents-base` and replaces `zetacomponents/base`,
  so a project that requires the upstream package gets this one in its place.
- The class names (`ezc*`) and the API are unchanged.
- Changes made in this fork are listed in `ChangeLog`.

## Installation

```bash
composer require se7enxweb/expcomponents-base
```

## Tests

```bash
composer update
vendor/bin/phpunit
```

The suite runs on every push for PHP 7.4, 8.0, 8.1, 8.2, 8.3, 8.4 and 8.5.

## License

Apache License 2.0, see `LICENSE.txt` and `NOTICE`.
