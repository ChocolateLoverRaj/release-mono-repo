# release-mono-repo
A GitHub Action to release multiple packages.

![Created with ](https://img.shields.io/badge/Created%20with-@programmerraj/create-3cb371?style=flat)
[![TS-Standard - Typescript Standard Style Guide](https://badgen.net/badge/code%20style/ts-standard/blue?icon=typescript)](https://github.com/standard/ts-standard)

## How it works
Uses [release-it](https://github.com/release-it/release-it) to release the packages.

## Inputs

### `increments_by_scope`
Increments gotten from [detect-increment](https://github.com/ChocolateLoverRaj/detect-increment)

### `new_packages`
Packages which need to be published without a version bump
