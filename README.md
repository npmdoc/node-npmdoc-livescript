# npmdoc-livescript

#### basic api documentation for  [livescript (v1.5.0)](http://livescript.net)  [![npm package](https://img.shields.io/npm/v/npmdoc-livescript.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-livescript) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-livescript.svg)](https://travis-ci.org/npmdoc/node-npmdoc-livescript)

#### LiveScript is a language which compiles to JavaScript. It has a straightforward mapping to JavaScript and allows you to write expressive code devoid of repetitive boilerplate. While LiveScript adds many features to assist in functional style programming,

[![NPM](https://nodei.co/npm/livescript.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/livescript)

- [https://npmdoc.github.io/node-npmdoc-livescript/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-livescript/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-livescript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-livescript/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-livescript/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-livescript/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "George Zahariev"
    },
    "bin": {
        "lsc": "./bin/lsc"
    },
    "browser": "./lib/browser.js",
    "bugs": {
        "url": "https://github.com/gkz/LiveScript/issues"
    },
    "dependencies": {
        "optionator": "~0.8.1",
        "prelude-ls": "~1.1.2",
        "source-map": "^0.5.6"
    },
    "description": "LiveScript is a language which compiles to JavaScript. It has a straightforward mapping to JavaScript and allows you to write expressive code devoid of repetitive boilerplate. While LiveScript adds many features to assist in functional style programming, ",
    "devDependencies": {
        "browserify": "^13.0.1",
        "istanbul": "~0.4.3",
        "jison": "0.4.17",
        "uglify-js": "~2.6.2"
    },
    "directories": {
        "lib": "./lib",
        "bin": "./bin"
    },
    "dist": {
        "shasum": "4fe7121c41217e4608e334eb9cbe1762e63e5566",
        "tarball": "https://registry.npmjs.org/livescript/-/livescript-1.5.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "lib",
        "bin",
        "README.md",
        "LICENSE"
    ],
    "gitHead": "9faea92f2a0e6cca90534acccab7db18efaf6b6c",
    "homepage": "http://livescript.net",
    "keywords": [
        "language",
        "compiler",
        "coffeescript",
        "coco",
        "javascript",
        "functional"
    ],
    "license": "MIT",
    "main": "./lib/",
    "maintainers": [
        {
            "name": "gkz"
        }
    ],
    "name": "livescript",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/gkz/LiveScript.git"
    },
    "scripts": {
        "posttest": "git checkout -- lib",
        "pretest": "make force && make force",
        "test": "make test",
        "test-harmony": "make test-harmony"
    },
    "version": "1.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
