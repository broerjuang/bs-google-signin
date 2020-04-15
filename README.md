# `bs-google-signin`

🚧 this is binding from
[`@react-native-community/google-signin`](https://github.com/react-native-community/google-signin).
The binding is still not complete and doesn't follow semver.

[![Build Status](https://github.com/ruang-guru/re-google-signin/workflows/Build/badge.svg)](https://github.com/ruang-guru/re-google-signin/actions)
[![Version](https://img.shields.io/npm/v/broerjuang/bs-google-signin.svg)](https://www.npmjs.com/@broerjuang/bs-google-signin)

[ReasonML](https://reasonml.github.io) /
[BuckleScript](https://bucklescript.github.io) bindings for
[`@react-native-community/google-signin`](https://github.com/react-native-community/google-signin).

Exposed as `GoogleSignin` module.

`@broerjuang/bs-google-signin` X.y._ means it's compatible with
`@react-native-community/google-signin` X.y._

## Installation

```console
npm install @broerjuang/bs-google-signin
# or
yarn add @broerjuang/bs-google-signin
```

`ruang-guru/re-google-signin` should be added to `bs-dependencies` in your
`bsconfig.json`. Something like

```diff
{
  //...
  "bs-dependencies": [
    "reason-react",
    "reason-react-native",
    // ...
+    "@broerjuang/bs-google-signin"
  ],
  //...
}
```

## Usage

### Types

#### `GoogleSignin.t`

...

### Methods

#### `GoogleSignin.method`

...

---

## Changelog

Check the [changelog](./CHANGELOG.md) for more informations about recent
releases.

---
