# npmtest-copy-to-clipboard

#### basic test coverage for  [copy-to-clipboard (v3.0.5)](https://github.com/sudodoki/copy-to-clipboard#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-copy-to-clipboard.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-copy-to-clipboard) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-copy-to-clipboard.svg)](https://travis-ci.org/npmtest/node-npmtest-copy-to-clipboard)

#### Copy stuff into clipboard using JS with fallbacks

[![NPM](https://nodei.co/npm/copy-to-clipboard.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/copy-to-clipboard)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-copy-to-clipboard/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-copy-to-clipboard/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-copy-to-clipboard/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-copy-to-clipboard/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-copy-to-clipboard/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-copy-to-clipboard/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-copy-to-clipboard/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-copy-to-clipboard/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-copy-to-clipboard/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-copy-to-clipboard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-copy-to-clipboard/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-copy-to-clipboard/build/test-report.html](https://npmtest.github.io/node-npmtest-copy-to-clipboard/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-copy-to-clipboard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-copy-to-clipboard/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-copy-to-clipboard/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-copy-to-clipboard/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-copy-to-clipboard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-copy-to-clipboard/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-copy-to-clipboard/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-copy-to-clipboard/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "sudodoki"
    },
    "bugs": {
        "url": "https://github.com/sudodoki/copy-to-clipboard/issues"
    },
    "contributors": [
        {
            "name": "Aleksej Shvajka",
            "url": "https://github.com/shvaikalesh"
        }
    ],
    "dependencies": {
        "toggle-selection": "^1.0.3"
    },
    "description": "Copy stuff into clipboard using JS with fallbacks",
    "devDependencies": {
        "browserify": "^13.0.1",
        "nightwatch": "^0.9.1",
        "node-static": "^0.7.7",
        "selenium-server-standalone-jar": "2.53.0"
    },
    "directories": {
        "example": "example"
    },
    "dist": {
        "shasum": "4cd40e7c2ee159bc72d4f06b5bec8f9e0a1a3442",
        "tarball": "https://registry.npmjs.org/copy-to-clipboard/-/copy-to-clipboard-3.0.5.tgz"
    },
    "gitHead": "7f3001c5f3c4669ad4446800973934e35ce166b9",
    "homepage": "https://github.com/sudodoki/copy-to-clipboard#readme",
    "keywords": [
        "clipboard",
        "copy",
        "browser"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "sudodoki"
        }
    ],
    "name": "copy-to-clipboard",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sudodoki/copy-to-clipboard.git"
    },
    "scripts": {
        "pretest": "browserify ./index.js -o ./example/index.js --standalone copyToClipboard",
        "test": "nightwatch"
    },
    "version": "3.0.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
