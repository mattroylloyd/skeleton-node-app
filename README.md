# skeleton-node-app

A basic node app installation with test suite set up using [jest](https://jestjs.io/docs/en/getting-started).

## Installation

Install project dependencies using [yarn](https://classic.yarnpkg.com/en/):
```bash
yarn
```

Or [npm](https://www.npmjs.com/get-npm):
```bash
npm install
```

## Usage

### Tests

You can run the tests by running:

```bash
yarn test
```
or
```
npm run test
```
Example output:
```
yarn run v1.22.4
$ jest
 PASS  src/sum.test.js
  ✓ adds 1 + 2 to equal 3 (1 ms)

Test Suites: 1 passed, 1 total
Tests:       1 passed, 1 total
Snapshots:   0 total
Time:        3.272 s, estimated 4 s
Ran all test suites.
✨  Done in 5.39s.
```

### Web app

You can also run the express js hello world app by running:
```bash
node app.js
```

You should then be able to see the app at http://localhost:3000

## License
[MIT](https://choosealicense.com/licenses/mit/)
