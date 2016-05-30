# @spencerhakim/eslint-config
Shared ESLint config for my personal projects

[![Build Status](https://travis-ci.org/spencerhakim/node-eslint-config.svg?branch=master)](https://travis-ci.org/spencerhakim/node-eslint-config)

### Install
```
$ npm install @spencerhakim/eslint-config --save-dev
```

You must also `npm install` the following peer dependencies:
- `eslint@2.x` (obviously)
- `babel-eslint@5.x`
- `eslint-plugin-babel@3.x`

The browser config additionally requires:
- `eslint-plugin-html@1.x`

The React config additionally requires:
- `eslint-plugin-react@5.x`

### Usage
`.eslintrc`
```json
{
  "extends": "trustpilot"
}
```

`.eslintrc` for Mocha tests
```json
{
  "extends": "trustpilot/test"
}
```

`.eslintrc` for React and JSX
```json
{
  "extends": "trustpilot/react"
}
```

`.eslintrc` for browsers
```json
{
  "extends": "trustpilot/browser"
}
```
