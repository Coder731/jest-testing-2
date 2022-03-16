itpod /workspace/jest-testing-2 (main) $ npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help init` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (jest-testing-2) 
version: (1.0.0) 
description: 
entry point: (index.js) 
test command: jest
git repository: (https://github.com/Coder731/jest-testing-2.git) 
keywords: 
author: 
license: (ISC) 
About to write to /workspace/jest-testing-2/package.json:

{
  "name": "jest-testing-2",
  "version": "1.0.0",
  "description": "following tutorial",
  "main": "index.js",
  "scripts": {
    "test": "jest"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/Coder731/jest-testing-2.git"
  },
  "author": "",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/Coder731/jest-testing-2/issues"
  },
  "homepage": "https://github.com/Coder731/jest-testing-2#readme"
}


Is this OK? (yes) 
npm notice 
npm notice New minor version of npm available! 8.1.2 -> 8.5.4
npm notice Changelog: https://github.com/npm/cli/releases/tag/v8.5.4
npm notice Run npm install -g npm@8.5.4 to update!
npm notice 
gitpod /workspace/jest-testing-2 (main) $ npm install --save-dev jest

added 332 packages, and audited 333 packages in 11s

28 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
gitpod /workspace/jest-testing-2 (main) $ npm test

> jest-testing-2@1.0.0 test
> jest

No tests found, exiting with code 1
Run with `--passWithNoTests` to exit with code 0
In /workspace/jest-testing-2
  2 files checked.
  testMatch: **/__tests__/**/*.[jt]s?(x), **/?(*.)+(spec|test).[tj]s?(x) - 0 matches
  testPathIgnorePatterns: /node_modules/ - 2 matches
  testRegex:  - 0 matches
Pattern:  - 0 matches
gitpod /workspace/jest-testing-2 (main) $ 