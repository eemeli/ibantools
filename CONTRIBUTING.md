# How to contribute

:+1: First off, thanks for taking the time to contribute!

This project adheres to the Contributor Covenant [code of conduct](.github/CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code.

* Clone this repo and run `npm install`.
* Write tests for your changes in `test/IBANToolsTest.ts`.
* Do not write more tests in `karma/ibantoolsSpec.js` unless module have problem with loading using AMD.
* Before making pull requests run `gulp all && gulp test && gulp karma`.
* Make sure that test coverage stays at 100%.
* Try not to make pull requests with changes in `dist`, `jsnext` or `build` directories.
