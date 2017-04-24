# npmtest-requireg

#### basic test coverage for  [requireg (v0.1.6)](http://github.com/h2non/requireg)  [![npm package](https://img.shields.io/npm/v/npmtest-requireg.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-requireg) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-requireg.svg)](https://travis-ci.org/npmtest/node-npmtest-requireg)

#### Require and resolve global modules like a boss

[![NPM](https://nodei.co/npm/requireg.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/requireg)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-requireg/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-requireg/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-requireg/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-requireg/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-requireg/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-requireg/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-requireg/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-requireg/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-requireg/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-requireg/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-requireg/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-requireg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-requireg/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-requireg/build/test-report.html](https://npmtest.github.io/node-npmtest-requireg/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-requireg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-requireg/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-requireg/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-requireg/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-requireg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-requireg/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-requireg/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-requireg/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/h2non/requireg/issues"
    },
    "contributors": [
        {
            "name": "Tomas Aparicio"
        },
        {
            "name": "Eugene Sharygin",
            "url": "https://github.com/eush77"
        }
    ],
    "dependencies": {
        "rc": "~1.0.0",
        "resolve": "~0.6.1"
    },
    "description": "Require and resolve global modules like a boss",
    "devDependencies": {
        "expect.js": "~0.2.0",
        "mocha": "~1.15.1",
        "rewire": "~2.3.1",
        "semver": "~2.2.1"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "205052aec2eaa2d8eb128abacf833b6a380a99b6",
        "tarball": "https://registry.npmjs.org/requireg/-/requireg-0.1.6.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "d7f4339ff5af321e8d80b2746b579cbe04ce39f1",
    "homepage": "http://github.com/h2non/requireg",
    "keywords": [
        "global",
        "npm",
        "modules",
        "module",
        "require",
        "import",
        "resolve"
    ],
    "licenses": "MIT",
    "main": "lib/requireg",
    "maintainers": [
        {
            "name": "h2non"
        }
    ],
    "name": "requireg",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/h2non/requireg.git"
    },
    "scripts": {
        "test": "mocha -u tdd --ui exports --reporter spec --slow 2000ms --bail"
    },
    "version": "0.1.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
