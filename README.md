# jest-esm-node

[Official Guide](https://jestjs.io/docs/en/ecmascript-modules)

## master

![workflows status @master](https://github.com/FlandreDaisuki/jest-esm-node/actions/workflows/jest.yaml/badge.svg?branch=master)

- `type: module` in package.json
- run jest with `--experimental-vm-modules` flag
- suffix `.js` for test files in esm
- suffix `.js` for `jest.config.js` in esm

## jest.config.cjs

![workflows status @jest.config.cjs](https://github.com/FlandreDaisuki/jest-esm-node/actions/workflows/jest.yaml/badge.svg?branch=jest.config.cjs)

- suffix `.cjs` for `jest.config.cjs` in cjs
- others are the same to [master](#master)
