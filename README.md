# test coverage for  [google-closure-compiler (v20170409.0.0)](https://developers.google.com/closure/compiler/)  [![npm package](https://img.shields.io/npm/v/npmtest-google-closure-compiler.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-google-closure-compiler) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-google-closure-compiler.svg)](https://travis-ci.org/npmtest/node-npmtest-google-closure-compiler)
#### Check, compile, optimize and compress Javascript with Closure-Compiler

[![NPM](https://nodei.co/npm/google-closure-compiler.png?downloads=true)](https://www.npmjs.com/package/google-closure-compiler)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-google-closure-compiler/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-google-closure-compiler/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-google-closure-compiler/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-google-closure-compiler%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-google-closure-compiler/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-google-closure-compiler/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-google-closure-compiler%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-google-closure-compiler/build/apidoc.html)

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
            "name": "Chad Killingsworth",
            "email": "chadkillingsworth@gmail.com"
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
        "shasum": "dc1be29a9f7eef8611364533b271b9fac757c970",
        "tarball": "https://registry.npmjs.org/google-closure-compiler/-/google-closure-compiler-20170409.0.0.tgz"
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
    "gitHead": "da10641e0ef4cfbcaa51e01d3fa5074f839be69a",
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
            "name": "blickly",
            "email": "blickly+npm@google.com"
        },
        {
            "name": "brad4d",
            "email": "bradfordcsmith@google.com"
        },
        {
            "name": "chadhikes",
            "email": "chadkillingsworth@gmail.com"
        },
        {
            "name": "dominator008",
            "email": "zhoumotongxue008@gmail.com"
        },
        {
            "name": "joeltine",
            "email": "jmarti221@gmail.com"
        }
    ],
    "name": "google-closure-compiler",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/google/closure-compiler-npm.git"
    },
    "scripts": {
        "pretest": "./build_compiler.js",
        "test": "mocha"
    },
    "version": "20170409.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
