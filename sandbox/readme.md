# Sandbox

For testing bugfixes while staying in the main repo. Especially useful for getting debug output.

Currently configured for https://github.com/mochajs/mocha/issues/5355 based off https://github.com/mochajs/mocha/pull/5379.

1. `cd` here
1. `DEBUG=* node ../bin/mocha.js`

- Mocha will use `/.mocharc.yml` at the root of the repo, so feel free to customize that for light testing
- Debug output provided by https://npmjs.com/debug
