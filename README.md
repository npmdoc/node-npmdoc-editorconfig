# npmdoc-editorconfig

#### api documentation for  editorconfig (v0.13.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-editorconfig.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-editorconfig) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-editorconfig.svg)](https://travis-ci.org/npmdoc/node-npmdoc-editorconfig)

#### EditorConfig File Locator and Interpreter for Node.js

[![NPM](https://nodei.co/npm/editorconfig.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/editorconfig)

- [https://npmdoc.github.io/node-npmdoc-editorconfig/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-editorconfig/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-editorconfig/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-editorconfig/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-editorconfig/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-editorconfig/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "editorconfig",
    "version": "0.13.2",
    "description": "EditorConfig File Locator and Interpreter for Node.js",
    "keywords": [
        "editorconfig",
        "core"
    ],
    "main": "editorconfig.js",
    "bin": {
        "editorconfig": "bin/editorconfig"
    },
    "contributors": [
        "Hong Xu (topbug.net)",
        "Jed Mao (https://github.com/jedmao/)",
        "Trey Hunner (http://treyhunner.com)"
    ],
    "directories": {
        "bin": "./bin",
        "lib": "./lib"
    },
    "scripts": {
        "pretest": "cmake .",
        "test": "npm run lint && ctest .",
        "test-verbose": "npm run lint && ctest -VV --output-on-failure .",
        "lint": "eclint check --indent_size ignore editorconfig.js README.md \"bin/**\" \"lib/**\""
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/editorconfig/editorconfig-core-js.git"
    },
    "bugs": "https://github.com/editorconfig/editorconfig-core-js/issues",
    "author": "EditorConfig Team",
    "license": {
        "type": "MIT",
        "url": "http://editorconfig.mit-license.org/2012"
    },
    "dependencies": {
        "bluebird": "^3.0.5",
        "commander": "^2.9.0",
        "lru-cache": "^3.2.0",
        "sigmund": "^1.0.1"
    },
    "devDependencies": {
        "eclint": "^1.1.5",
        "mocha": "^2.3.4",
        "should": "^7.1.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
