# @dwp/eslint-config-jasmine

Shareable [`eslint`](http://eslint.org) config enforcing our lint and style convention for the [`jasmine`](https://jasmine.github.io/) test framework.

## Getting started

```sh
npm install --save-dev @dwp/eslint-config-base eslint
```

## Rules

Add an `.eslintrc.js` file that looks something like:

```js
module.exports = require('@dwp/eslint-config-jasmine');
```

You can add your own rules to enhance this, but in doing so please ensure you don't weaken the baseline ruleset.

Don't use `.eslintrc` (low precedence) or `package.json` (even lower, and just plain bad!), lest you incur the wrath of a patient adversary.

## Linting

Add `eslint` to your test suite like this, or see our [package.json](package.json) for an example of how we do it:

```json
  "test": "eslint ."
```
