# ponsfrilus-commit-types

*This is a fork from [conventional-commit-types](https://github.com/commitizen/conventional-commit-types).*

Status:
[![npm version](https://img.shields.io/npm/v/ponsfrilus-commit-types.svg?style=flat-square)](https://www.npmjs.org/package/ponsfrilus-commit-types)
[![npm downloads](https://img.shields.io/npm/dm/ponsfrilus-commit-types.svg?style=flat-square)](http://npm-stat.com/charts.html?package=ponsfrilus-commit-types&from=2019-01-01)
[![Build Status](https://img.shields.io/travis/ponsfrilus/ponsfrilus-commit-types.svg?style=flat-square)](https://travis-ci.org/ponsfrilus/ponsfrilus-commit-types)


## Spec

Exports an object with a `types` key whose value is an object whose keys are
type names and whose values are objects with key-value pairs such as
`description` as string, optional `title` as string, etc. See
[index.json](index.json). Any alternatives should follow the same spec.

## Prefixes

I do like **bracketed 3 letters capitalized** prefixes. A good part of them are
adapted from the original
[conventional-commit-types](https://github.com/commitizen/conventional-commit-types/blob/master/index.json) repo:

```
* [ADD] → ADD: When the project welcome new files

* [BLD] → BUILD: Changes that affect the build system or external dependencies
  (example scopes: gulp, broccoli, npm)

* [BTF] → BEAUTIFULLAGE: (aka style) Changes that do not affect the meaning of
  the code (white-space, formatting, missing semi-colons, etc)

* [C.I] → CONTINUOUS INTEGRATION: Changes to the CI configuration files and
  scripts

* [DOC] → DOCUMENTATION: Documentation only changes

* [FIX] → FIXE: A bug fix

* [FT.] → FEATURE: A new feature

* [HOC] → HOUSE CLEANING: Changes that make the repository more clean (wiping,
  cleaning, mopping)

* [IGN] → IGNORE: When adding a .gitignore file or similar

* [OTH] → OTHER: Other changes that don't modify src or test files

* [PRF] → PERFORMANCE: A code change that improves performance

* [RFA] → REFACTOR: A code change that neither fixes a bug nor adds a feature

* [RVT] → REVERT: Reverts a previous commit

* [STY] → STYLE: Changes that mainly change the style, look and feel or visual
  appearance

* [TST] → TEST: Adding missing tests or correcting existing tests

* [TYP] → TYPO: An error (as of spelling) in typed or typeset material

* [VER] → VERSION: Bump version

* [WIP] → WORK IN PROGRESS: e.g. in case of fire
```

Please note they are sorted by prefixes in alphabetical order.

## Infos

* [cz-ponsfrilus-changelog](https://github.com/ponsfrilus/cz-ponsfrilus-changelog)
* [ponsfrilus-commit-types](https://github.com/ponsfrilus/ponsfrilus-commit-types)

## ToDo

* Travis
* Changelog
  * https://github.com/conventional-changelog/conventional-changelog
* Better semantic-release / standard-version
  * https://github.com/conventional-changelog/standard-version
  * https://github.com/semantic-release/semantic-release