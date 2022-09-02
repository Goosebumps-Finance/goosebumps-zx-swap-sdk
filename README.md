# Goosebumps Zx-SDK

Forked from the [Goosebumps SDK](https://github.com/CryptoSnowPrince/goosebumps-swap-sdk/commit/c03574efe8f6976f9d7aa578899fb7944c597a6f).

You can refer to the Uniswap SDK documentation [uniswap.org](https://docs.uniswap.org/sdk/2.0.0/).

## Running tests

To run the tests, follow these steps. You must have at least node v10 and [yarn](https://yarnpkg.com/) installed.

First clone the repository:

```sh
git clone https://github.com/CryptoSnowPrince/goosebumps-zx-swap-sdk.git
```

Move into the goosebumps-zx-swap-sdk working directory

```sh
cd goosebumps-zx-swap-sdk/
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
 PASS  test/constants.test.ts
 PASS  test/pair.test.ts
 PASS  test/fraction.test.ts
 PASS  test/miscellaneous.test.ts
 PASS  test/entities.test.ts
 PASS  test/trade.test.ts

Test Suites: 1 skipped, 6 passed, 6 of 7 total
Tests:       3 skipped, 82 passed, 85 total
Snapshots:   0 total
Time:        5.091s
Ran all test suites.
✨  Done in 6.61s.
```
