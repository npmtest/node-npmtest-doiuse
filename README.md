# npmtest-doiuse

#### basic test coverage for  [doiuse (v2.6.0)](https://github.com/anandthakker/doiuse)  [![npm package](https://img.shields.io/npm/v/npmtest-doiuse.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-doiuse) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-doiuse.svg)](https://travis-ci.org/npmtest/node-npmtest-doiuse)

#### Lint CSS for browser support against caniuse database.

[![NPM](https://nodei.co/npm/doiuse.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/doiuse)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-doiuse/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-doiuse/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-doiuse/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-doiuse/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-doiuse/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-doiuse/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-doiuse/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-doiuse/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-doiuse/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-doiuse/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-doiuse/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-doiuse/build/test-report.html](https://npmtest.github.io/node-npmtest-doiuse/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-doiuse/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-doiuse/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-doiuse/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-doiuse/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-doiuse/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-doiuse/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-doiuse/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-doiuse/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "doiuse",
    "version": "2.6.0",
    "description": "Lint CSS for browser support against caniuse database.",
    "main": "lib/doiuse.js",
    "scripts": {
        "test": "standard && tape test/*.js",
        "babel": "babel -d lib/ src/",
        "pretest": "npm run babel",
        "prepublish": "npm run babel"
    },
    "bin": "./cli.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/anandthakker/doiuse.git"
    },
    "keywords": [
        "lint",
        "css",
        "browser",
        "support"
    ],
    "author": "Anand Thakker",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/anandthakker/doiuse/issues"
    },
    "homepage": "https://github.com/anandthakker/doiuse",
    "dependencies": {
        "browserslist": "^1.1.1",
        "caniuse-db": "^1.0.30000187",
        "css-rule-stream": "^1.1.0",
        "duplexer2": "0.0.2",
        "jsonfilter": "^1.1.2",
        "ldjson-stream": "^1.2.1",
        "lodash": "^4.0.0",
        "multimatch": "^2.0.0",
        "postcss": "^5.0.8",
        "source-map": "^0.4.2",
        "through2": "^0.6.3",
        "yargs": "^3.5.4"
    },
    "devDependencies": {
        "babel": "^5.2.13",
        "mock-fs": "^3.12.1",
        "postcss-import": "^7.1.3",
        "standard": "^8.1.0",
        "tape": "^4.0.0"
    },
    "standard": {
        "ignore": [
            "data/*.js"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
