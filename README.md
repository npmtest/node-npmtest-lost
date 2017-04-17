# test coverage for  [lost (v8.0.0)](http://lostgrid.org)  [![npm package](https://img.shields.io/npm/v/npmtest-lost.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lost) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lost.svg)](https://travis-ci.org/npmtest/node-npmtest-lost)
#### LostGrid is a powerful grid system built in PostCSS that works with any preprocessor and even vanilla CSS.

[![NPM](https://nodei.co/npm/lost.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lost)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lost/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lost/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lost/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lost/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lost/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lost/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lost/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-lost/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-lost/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lost/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-lost/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-lost/build/test-report.html](https://npmtest.github.io/node-npmtest-lost/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-lost/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lost/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-lost/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lost/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lost/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lost/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lost/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lost/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Cory Simmons & Peter Ramsing",
        "url": "http://peter.coffee"
    },
    "bugs": {
        "url": "https://github.com/peterramsing/lost/issues"
    },
    "dependencies": {
        "object-assign": "^4.1.0",
        "postcss": "^5.2.8"
    },
    "description": "LostGrid is a powerful grid system built in PostCSS that works with any preprocessor and even vanilla CSS.",
    "devDependencies": {
        "chai": "^3.5",
        "eslint": "^3.12",
        "istanbul": "^0.4",
        "mocha": "^3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "7ab03254f1106b6940abb2045c0e38f821a73475",
        "tarball": "https://registry.npmjs.org/lost/-/lost-8.0.0.tgz"
    },
    "gitHead": "396d6bddd38f5237159d37d834ad6df42d2f8cb7",
    "homepage": "http://lostgrid.org",
    "keywords": [
        "grid",
        "fraction",
        "ratio",
        "postcss",
        "postcss-plugin"
    ],
    "license": "MIT",
    "main": "lost.js",
    "maintainers": [
        {
            "name": "corysimmons"
        },
        {
            "name": "peterramsing"
        }
    ],
    "name": "lost",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/peterramsing/lost.git"
    },
    "scripts": {
        "lint": "eslint lib/*.js lost.js",
        "test": "istanbul cover node_modules/mocha/bin/_mocha -- test/*.js"
    },
    "version": "8.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
