# npmtest-base64-js

#### basic test coverage for  [base64-js (v1.2.0)](https://github.com/beatgammit/base64-js)  [![npm package](https://img.shields.io/npm/v/npmtest-base64-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-base64-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-base64-js.svg)](https://travis-ci.org/npmtest/node-npmtest-base64-js)

#### Base64 encoding/decoding in pure JS

[![NPM](https://nodei.co/npm/base64-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/base64-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-base64-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-base64-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-base64-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-base64-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-base64-js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-base64-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-base64-js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-base64-js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-base64-js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-base64-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-base64-js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-base64-js/build/test-report.html](https://npmtest.github.io/node-npmtest-base64-js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-base64-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-base64-js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-base64-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-base64-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-base64-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-base64-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-base64-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-base64-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "base64-js",
    "version": "1.2.0",
    "description": "Base64 encoding/decoding in pure JS",
    "keywords": [
        "base64"
    ],
    "homepage": "https://github.com/beatgammit/base64-js",
    "bugs": {
        "url": "https://github.com/beatgammit/base64-js/issues"
    },
    "license": "MIT",
    "author": "T. Jameson Little <t.jameson.little@gmail.com>",
    "files": [
        "test",
        "index.js",
        "base64js.min.js"
    ],
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/beatgammit/base64-js.git"
    },
    "scripts": {
        "build": "browserify -s base64js -r ./ | uglifyjs -m > base64js.min.js",
        "lint": "standard",
        "test": "npm run lint && npm run unit",
        "unit": "tape test/*.js"
    },
    "devDependencies": {
        "benchmark": "^2.1.0",
        "browserify": "^13.0.0",
        "standard": "*",
        "tape": "4.x",
        "uglify-js": "^2.6.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
