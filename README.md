# npmtest-google-closure-compiler

#### basic test coverage for  [google-closure-compiler (v20170423.0.0)](https://developers.google.com/closure/compiler/)  [![npm package](https://img.shields.io/npm/v/npmtest-google-closure-compiler.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-google-closure-compiler) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-google-closure-compiler.svg)](https://travis-ci.org/npmtest/node-npmtest-google-closure-compiler)

#### Check, compile, optimize and compress Javascript with Closure-Compiler

[![NPM](https://nodei.co/npm/google-closure-compiler.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/google-closure-compiler)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-google-closure-compiler/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-google-closure-compiler/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-google-closure-compiler/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-google-closure-compiler/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-google-closure-compiler/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-google-closure-compiler/build/test-report.html](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-google-closure-compiler/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-google-closure-compiler/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-google-closure-compiler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-google-closure-compiler/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/google/closure-compiler/issues"
    },
    "contributors": [
        {
            "name": "Chad Killingsworth"
        }
    ],
    "dependencies": {
        "chalk": "^1.0.0",
        "vinyl": "^2.0.1",
        "vinyl-sourcemaps-apply": "^0.2.0"
    },
    "description": "Check, compile, optimize and compress Javascript with Closure-Compiler",
    "devDependencies": {
        "gulp": "^3.9.0",
        "gulp-mocha": "^4.0.1",
        "gulp-sourcemaps": "^2.4.1",
        "lodash": "^4.6.1",
        "mocha": "^3.2.0",
        "ncp": "^2.0.0",
        "semver": "^5.1.0",
        "should": "^11.2.0",
        "stream-assert": "^2.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "475c6a2f4512fd7fdbacb32997b2e1ab1ca6fff8",
        "tarball": "https://registry.npmjs.org/google-closure-compiler/-/google-closure-compiler-20170423.0.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "lib/",
        "compiler.jar",
        "index.js",
        "package.json",
        "contrib/",
        "README.md"
    ],
    "gitHead": "a89bfe8bc212d4063eecc7891befe8e144130c13",
    "homepage": "https://developers.google.com/closure/compiler/",
    "keywords": [
        "javascript",
        "compiler",
        "optimizer",
        "minifier",
        "closure",
        "gulpplugin",
        "gruntplugin"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "blickly"
        },
        {
            "name": "brad4d"
        },
        {
            "name": "chadhikes"
        },
        {
            "name": "dominator008"
        },
        {
            "name": "joeltine"
        }
    ],
    "name": "google-closure-compiler",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/google/closure-compiler-npm.git"
    },
    "scripts": {
        "pretest": "./build_compiler.js",
        "test": "mocha"
    },
    "version": "20170423.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
