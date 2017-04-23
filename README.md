# npmtest-aerospike

#### basic test coverage for  [aerospike (v2.5.2)](https://github.com/aerospike/aerospike-client-nodejs)  [![npm package](https://img.shields.io/npm/v/npmtest-aerospike.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-aerospike) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-aerospike.svg)](https://travis-ci.org/npmtest/node-npmtest-aerospike)

#### Aerospike Client Library

[![NPM](https://nodei.co/npm/aerospike.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/aerospike)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-aerospike/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-aerospike/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-aerospike/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-aerospike/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-aerospike/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-aerospike/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-aerospike/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-aerospike/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-aerospike/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-aerospike/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-aerospike/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-aerospike/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-aerospike/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-aerospike/build/test-report.html](https://npmtest.github.io/node-npmtest-aerospike/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-aerospike/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-aerospike/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-aerospike/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-aerospike/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-aerospike/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-aerospike/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-aerospike/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-aerospike/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/aerospike/aerospike-client-nodejs/issues"
    },
    "cpu": [
        "x64"
    ],
    "dependencies": {
        "nan": "~2.3.0",
        "webworker-threads": "^0.7"
    },
    "description": "Aerospike Client Library",
    "devDependencies": {
        "deasync": "^0.1.4",
        "expect.js": "^0.3",
        "ink-docstrap": "^1.1.0",
        "jsdoc": "^3.4.0",
        "mocha": "^3.0",
        "standard": "^9.0",
        "yargs": "1.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "fe48e37915972681a25667143e9029c0b0b7235b",
        "tarball": "https://registry.npmjs.org/aerospike/-/aerospike-2.5.2.tgz"
    },
    "engines": {
        "node": ">=0.12"
    },
    "gypfile": true,
    "homepage": "https://github.com/aerospike/aerospike-client-nodejs",
    "license": "Apache-2.0",
    "main": "lib/aerospike",
    "maintainers": [
        {
            "name": "aerospike"
        },
        {
            "name": "chris-aerospike.com"
        },
        {
            "name": "jhecking-aerospike"
        }
    ],
    "name": "aerospike",
    "optionalDependencies": {
        "webworker-threads": "^0.7"
    },
    "os": [
        "linux",
        "darwin"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/aerospike/aerospike-client-nodejs.git"
    },
    "scripts": {
        "apidocs": "jsdoc -c jsdoc.json",
        "install": "node-gyp rebuild",
        "preversion": "npm test",
        "test": "standard && ./scripts/shuffle_tests"
    },
    "standard": {
        "ignore": [
            "apidocs"
        ]
    },
    "tags": [
        "aerospike",
        "database",
        "nosql"
    ],
    "version": "2.5.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
