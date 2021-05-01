# Hubdao SDK

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
[![Actions Status](https://github.com/hub-dao/hubdao-sdk/workflows/CI/badge.svg)](https://github.com/hub-dao/hubdao-sdk)
[![npm version](https://img.shields.io/npm/v/@pancakeswap-lib/sdk/latest.svg)](https://www.npmjs.com/package/@hubdao-finance/hubdao-sdk/v/latest)

## Running tests

To run the tests, follow these steps. You must have at least node v10 and [yarn](https://yarnpkg.com/) installed.

First clone the repository:

```sh
git clone https://github.com/hub-dao/hubdao-sdk.git
```

Move into the pancakeswap-sdk working directory

```sh
cd pancakeswap-sdk/
```

Install dependencies

```sh
yarn install
```

Run tests

```sh
yarn test
```

You should see output like the following:

```sh
yarn run v1.22.4
$ tsdx test
 PASS  test/route.test.ts
 PASS  test/pair.test.ts
 PASS  test/router.test.ts
 PASS  test/fraction.test.ts
 PASS  test/miscellaneous.test.ts
 PASS  test/trade.test.ts
 PASS  test/token.test.ts
 PASS  test/constants.test.ts
 PASS  test/entities.test.ts

Test Suites: 1 skipped, 9 passed, 9 of 10 total
Tests:       3 skipped, 123 passed, 126 total
Snapshots:   0 total
Time:        3.937s, estimated 4s
Ran all test suites.
✨  Done in 5.55s.
```
