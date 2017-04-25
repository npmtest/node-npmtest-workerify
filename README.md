# npmtest-workerify

#### basic test coverage for  [workerify (v0.3.0)](https://github.com/shama/workerify)  [![npm package](https://img.shields.io/npm/v/npmtest-workerify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-workerify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-workerify.svg)](https://travis-ci.org/npmtest/node-npmtest-workerify)

#### Transform web workers into browserified inline Blobs with browserify.

[![NPM](https://nodei.co/npm/workerify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/workerify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-workerify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-workerify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-workerify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-workerify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-workerify/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-workerify/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-workerify/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-workerify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-workerify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-workerify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-workerify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-workerify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-workerify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-workerify/build/test-report.html](https://npmtest.github.io/node-npmtest-workerify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-workerify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-workerify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-workerify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-workerify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-workerify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-workerify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-workerify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-workerify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kyle Robinson Young",
        "url": "http://dontkry.com"
    },
    "bugs": {
        "url": "https://github.com/shama/workerify/issues"
    },
    "dependencies": {
        "browserify": "~3.41.0",
        "falafel": "~0.2.1",
        "jsesc": "~0.3.0",
        "through": "~2.3.4"
    },
    "description": "Transform web workers into browserified inline Blobs with browserify.",
    "devDependencies": {
        "beefy": "~1.1.0",
        "tape": "~2.12.3",
        "workerstream": "~1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "5d8e6ce9b6db7bf139d2dd8beacf5a88827449f6",
        "tarball": "https://registry.npmjs.org/workerify/-/workerify-0.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "LICENSE-MIT",
        "index.js"
    ],
    "homepage": "https://github.com/shama/workerify",
    "keywords": [
        "worker",
        "browserify",
        "transform"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/shama/workerify/blob/master/LICENSE-MIT"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "shama"
        }
    ],
    "name": "workerify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/shama/workerify.git"
    },
    "scripts": {
        "start": "beefy example/index.js -- -t ./",
        "test": "browserify test/test.js -t ./ -o test/out.js"
    },
    "testling": {
        "files": "test/out.js",
        "browsers": [
            "ielatest",
            "chrome/latest",
            "firefoxlatest",
            "safari/latest",
            "opera/latest",
            "iphone/latest",
            "ipad/latest",
            "android-browser/latest"
        ]
    },
    "version": "0.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
