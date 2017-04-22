# npmtest-array-flatten

#### basic test coverage for  [array-flatten (v2.1.1)](https://github.com/blakeembrey/array-flatten)  [![npm package](https://img.shields.io/npm/v/npmtest-array-flatten.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-array-flatten) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-array-flatten.svg)](https://travis-ci.org/npmtest/node-npmtest-array-flatten)

#### Flatten nested arrays

[![NPM](https://nodei.co/npm/array-flatten.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/array-flatten)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-array-flatten/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-array-flatten/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-array-flatten/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-array-flatten/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-array-flatten/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-array-flatten/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-array-flatten/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-array-flatten/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-array-flatten/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-array-flatten/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-array-flatten/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-array-flatten/build/test-report.html](https://npmtest.github.io/node-npmtest-array-flatten/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-array-flatten/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-array-flatten/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-array-flatten/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-array-flatten/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-array-flatten/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-array-flatten/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-array-flatten/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-array-flatten/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Blake Embrey",
        "url": "http://blakeembrey.me"
    },
    "bugs": {
        "url": "https://github.com/blakeembrey/array-flatten/issues"
    },
    "dependencies": {},
    "description": "Flatten nested arrays",
    "devDependencies": {
        "benchmarked": "^0.2.5",
        "istanbul": "^0.4.0",
        "mocha": "^3.1.2",
        "standard": "^8.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "426bb9da84090c1838d812c8150af20a8331e296",
        "tarball": "https://registry.npmjs.org/array-flatten/-/array-flatten-2.1.1.tgz"
    },
    "files": [
        "array-flatten.js",
        "array-flatten.d.ts",
        "LICENSE"
    ],
    "gitHead": "b5619025bfb5d624fc2106ec81f9fdecf5419e04",
    "homepage": "https://github.com/blakeembrey/array-flatten",
    "keywords": [
        "array",
        "flatten",
        "arguments",
        "depth",
        "fast",
        "for"
    ],
    "license": "MIT",
    "main": "array-flatten.js",
    "maintainers": [
        {
            "name": "blakeembrey"
        }
    ],
    "name": "array-flatten",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/blakeembrey/array-flatten.git"
    },
    "scripts": {
        "benchmark": "node benchmark",
        "lint": "standard",
        "test": "npm run lint && npm run test-cov",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- -R spec --bail",
        "test-spec": "mocha -R spec --bail"
    },
    "typings": "array-flatten.d.ts",
    "version": "2.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
