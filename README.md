# test coverage for  [sane (v1.6.0)](https://github.com/amasad/sane)  [![npm package](https://img.shields.io/npm/v/npmtest-sane.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sane) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sane.svg)](https://travis-ci.org/npmtest/node-npmtest-sane)
#### Sane aims to be fast, small, and reliable file system watcher.

[![NPM](https://nodei.co/npm/sane.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sane)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sane/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sane/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sane/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sane/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sane/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sane/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sane/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sane/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sane/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sane/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sane/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sane/build/test-report.html](https://npmtest.github.io/node-npmtest-sane/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sane/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sane/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sane/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sane/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sane/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sane/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sane/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sane/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "amasad"
    },
    "bin": {
        "sane": "./src/cli.js"
    },
    "bugs": {
        "url": "https://github.com/amasad/sane/issues"
    },
    "dependencies": {
        "anymatch": "^1.3.0",
        "exec-sh": "^0.2.0",
        "fb-watchman": "^1.8.0",
        "minimatch": "^3.0.2",
        "minimist": "^1.1.1",
        "walker": "~1.0.5",
        "watch": "~0.10.0"
    },
    "description": "Sane aims to be fast, small, and reliable file system watcher.",
    "devDependencies": {
        "jshint": "^2.5.10",
        "mocha": "~1.17.1",
        "rimraf": "~2.2.6",
        "tmp": "0.0.27"
    },
    "directories": {},
    "dist": {
        "shasum": "9610c452307a135d29c1fdfe2547034180c46775",
        "tarball": "https://registry.npmjs.org/sane/-/sane-1.6.0.tgz"
    },
    "engines": {
        "node": ">=0.6.0"
    },
    "files": [
        "src",
        "index.js"
    ],
    "gitHead": "b9c60d9dd3c5a81f50ef0f05828038191fdfa68b",
    "homepage": "https://github.com/amasad/sane",
    "keywords": [
        "watch",
        "file",
        "fswatcher",
        "watchfile",
        "fs",
        "watching"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "amasad"
        },
        {
            "name": "stefanpenner"
        }
    ],
    "name": "sane",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/amasad/sane.git"
    },
    "scripts": {
        "prepublish": "jshint --config=.jshintrc src/ index.js && mocha --bail",
        "test": "jshint --config=.jshintrc src/ index.js && mocha --bail test/test.js && mocha --bail test/utils-test.js",
        "test:debug": "mocha debug --bail"
    },
    "version": "1.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
