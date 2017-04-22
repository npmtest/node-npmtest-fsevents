# npmtest-fsevents

#### basic test coverage for  [fsevents (v1.1.1)](https://github.com/strongloop/fsevents)  [![npm package](https://img.shields.io/npm/v/npmtest-fsevents.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fsevents) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fsevents.svg)](https://travis-ci.org/npmtest/node-npmtest-fsevents)

#### Native Access to Mac OS-X FSEvents

[![NPM](https://nodei.co/npm/fsevents.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fsevents)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fsevents/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fsevents/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fsevents/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fsevents/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fsevents/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fsevents/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fsevents/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fsevents/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fsevents/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fsevents/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fsevents/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fsevents/build/test-report.html](https://npmtest.github.io/node-npmtest-fsevents/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fsevents/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fsevents/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fsevents/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fsevents/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fsevents/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fsevents/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fsevents/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fsevents/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "fsevents",
    "version": "1.1.1",
    "description": "Native Access to Mac OS-X FSEvents",
    "main": "fsevents.js",
    "dependencies": {
        "nan": "^2.3.0",
        "node-pre-gyp": "^0.6.29"
    },
    "os": [
        "darwin"
    ],
    "engines": {
        "node": ">=0.8.0"
    },
    "scripts": {
        "install": "node install",
        "prepublish": "if [ $(npm -v | head -c 1) -lt 3 ]; then exit 1; fi && npm dedupe",
        "test": "tap ./test"
    },
    "binary": {
        "module_name": "fse",
        "module_path": "./lib/binding/{configuration}/{node_abi}-{platform}-{arch}/",
        "remote_path": "./v{version}/",
        "package_name": "{module_name}-v{version}-{node_abi}-{platform}-{arch}.tar.gz",
        "host": "https://fsevents-binaries.s3-us-west-2.amazonaws.com"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/strongloop/fsevents.git"
    },
    "keywords": [
        "fsevents",
        "mac"
    ],
    "author": "Philipp Dunkel <pip@pipobscure.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/strongloop/fsevents/issues"
    },
    "bundledDependencies": [
        "node-pre-gyp"
    ],
    "homepage": "https://github.com/strongloop/fsevents",
    "devDependencies": {
        "tap": "~0.4.8"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
