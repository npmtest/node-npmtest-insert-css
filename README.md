# npmtest-insert-css

#### basic test coverage for  [insert-css (v2.0.0)](https://github.com/substack/insert-css)  [![npm package](https://img.shields.io/npm/v/npmtest-insert-css.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-insert-css) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-insert-css.svg)](https://travis-ci.org/npmtest/node-npmtest-insert-css)

#### insert a string of css into the <head>

[![NPM](https://nodei.co/npm/insert-css.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/insert-css)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-insert-css/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-insert-css/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-insert-css/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-insert-css/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-insert-css/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-insert-css/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-insert-css/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-insert-css/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-insert-css/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-insert-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-insert-css/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-insert-css/build/test-report.html](https://npmtest.github.io/node-npmtest-insert-css/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-insert-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-insert-css/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-insert-css/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-insert-css/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-insert-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-insert-css/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-insert-css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-insert-css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "bugs": {
        "url": "https://github.com/substack/insert-css/issues"
    },
    "dependencies": {},
    "description": "insert a string of css into the <head>",
    "devDependencies": {
        "browserify": "^13.0.1",
        "budo": "^8.3.0",
        "computed-style": "^0.3.0",
        "dom-event": "^1.0.0",
        "tape": "^4.6.0",
        "tape-run": "^2.1.4"
    },
    "directories": {},
    "dist": {
        "shasum": "eb5d1097b7542f4c79ea3060d3aee07d053880f4",
        "tarball": "https://registry.npmjs.org/insert-css/-/insert-css-2.0.0.tgz"
    },
    "gitHead": "d13317dfd48d0ed7272526d8a58058ad719f3c91",
    "homepage": "https://github.com/substack/insert-css",
    "keywords": [
        "css",
        "insert",
        "dom",
        "browser",
        "browserify",
        "inject",
        "styles",
        "stylesheet",
        "style",
        "html",
        "head",
        "link"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jonaskello"
        },
        {
            "name": "substack"
        },
        {
            "name": "vvo"
        }
    ],
    "name": "insert-css",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/insert-css.git"
    },
    "scripts": {
        "example": "budo example.js",
        "test": "browserify test.js | tape-run"
    },
    "testling": {
        "files": "test.js",
        "browsers": [
            "ie/6..latest",
            "chrome/20..latest",
            "firefox/10..latest",
            "safari/latest",
            "opera/11.0..latest",
            "iphone/6",
            "ipad/6"
        ]
    },
    "version": "2.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
