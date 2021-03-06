# npmdoc-ascii-art

#### basic api documentation for  [ascii-art (v1.4.2)](https://github.com/khrome/ascii-art)  [![npm package](https://img.shields.io/npm/v/npmdoc-ascii-art.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ascii-art) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ascii-art.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ascii-art)

#### Ansi codes, figlet fonts, and ascii art. 100% JS

[![NPM](https://nodei.co/npm/ascii-art.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ascii-art)

- [https://npmdoc.github.io/node-npmdoc-ascii-art/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ascii-art/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ascii-art/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ascii-art/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ascii-art/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ascii-art/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Abbey Hawk Sparrow",
        "url": "http://patternweaver.com"
    },
    "bin": {
        "ascii-art": "./bin/ascii-art"
    },
    "bugs": {
        "url": "https://github.com/khrome/ascii-art/issues"
    },
    "contributors": [],
    "dependencies": {
        "browser-request": "0.3.3",
        "canvas": "*",
        "dirname-shim": "1.0.0",
        "jsftp": "*",
        "request": "2.79.0",
        "yargs": "*"
    },
    "description": "Ansi codes, figlet fonts, and ascii art. 100% JS",
    "devDependencies": {
        "color-difference": "*",
        "karma": "1.3.0",
        "karma-chrome-launcher": "*",
        "karma-mocha": "1.2.0",
        "karma-phantomjs-launcher": "1.0.2",
        "karma-requirejs": "1.1.0",
        "karma-should": "1.0.0",
        "mocha": "*",
        "requirejs": "2.3.2",
        "should": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "96f5f471b095e9702afc3cb29418486450cd17a1",
        "tarball": "https://registry.npmjs.org/ascii-art/-/ascii-art-1.4.2.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "3b3cb3ec376ef1d53efb9c61b584389d95d77ab7",
    "homepage": "https://github.com/khrome/ascii-art",
    "keywords": [
        "ascii",
        "figlet",
        "ansi",
        "terminal",
        "text",
        "command-line",
        "logging",
        "log",
        "xterm",
        "shell",
        "256",
        "rgb",
        "formatting",
        "tty",
        "styles",
        "style",
        "str",
        "string",
        "cli",
        "console",
        "terminal",
        "table",
        "compositing",
        "colors",
        "colour",
        "color",
        "chalk"
    ],
    "license": "MIT",
    "main": "ascii-art.js",
    "maintainers": [
        {
            "name": "khrome"
        }
    ],
    "name": "ascii-art",
    "optionalDependencies": {
        "canvas": "*",
        "jsftp": "*"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/khrome/ascii-art.git"
    },
    "scripts": {
        "browser-test": "karma start",
        "chalk-test": "mocha test/extras/kaolin-test.js",
        "sample": "node generate.js",
        "test": "mocha",
        "test-data": "node generate.js save"
    },
    "version": "1.4.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
