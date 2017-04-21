# npmdoc-webpack-bundle-size-analyzer

#### api documentation for  [webpack-bundle-size-analyzer (v2.6.0)](http://github.com/robertknight/webpack-bundle-size-analyzer)  [![npm package](https://img.shields.io/npm/v/npmdoc-webpack-bundle-size-analyzer.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-webpack-bundle-size-analyzer) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-webpack-bundle-size-analyzer.svg)](https://travis-ci.org/npmdoc/node-npmdoc-webpack-bundle-size-analyzer)

#### A utility to find how your dependencies are contributing to the size of your Webpack bundles

[![NPM](https://nodei.co/npm/webpack-bundle-size-analyzer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webpack-bundle-size-analyzer)

- [https://npmdoc.github.io/node-npmdoc-webpack-bundle-size-analyzer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webpack-bundle-size-analyzer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webpack-bundle-size-analyzer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webpack-bundle-size-analyzer/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-webpack-bundle-size-analyzer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-webpack-bundle-size-analyzer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "webpack-bundle-size-analyzer",
    "version": "2.6.0",
    "description": "A utility to find how your dependencies are contributing to the size of your Webpack bundles",
    "main": "build/src/index.js",
    "scripts": {
        "postversion": "git push && git push --tags && npm publish",
        "preversion": "npm test",
        "coverage": "jest --coverage --no-cache",
        "test": "make test",
        "version": "make clean && make"
    },
    "bin": {
        "webpack-bundle-size-analyzer": "./webpack-bundle-size-analyzer"
    },
    "keywords": [
        "webpack"
    ],
    "author": "Robert Knight <robertknight@gmail.com>",
    "license": "ISC",
    "dependencies": {
        "commander": "^2.7.1",
        "filesize": "^3.1.2",
        "humanize": "0.0.9"
    },
    "files": [
        "build/src",
        "webpack-bundle-size-analyzer"
    ],
    "homepage": "http://github.com/robertknight/webpack-bundle-size-analyzer",
    "repository": {
        "type": "git",
        "url": "http://github.com/robertknight/webpack-bundle-size-analyzer.git"
    },
    "devDependencies": {
        "@types/commander": "^2.3.31",
        "@types/jest": "^19.2.2",
        "@types/node": "^6.0.58",
        "jest": "^19.0.2",
        "ts-jest": "^19.0.5",
        "typescript": "^2.1.4"
    },
    "jest": {
        "coverageReporters": [
            "text-summary",
            "html",
            "lcovonly"
        ],
        "moduleFileExtensions": [
            "ts",
            "tsx",
            "js"
        ],
        "transform": {
            ".(ts|tsx)": "<rootDir>/node_modules/ts-jest/preprocessor.js"
        },
        "testResultsProcessor": "<rootDir>/node_modules/ts-jest/coverageprocessor.js",
        "testRegex": "/tests/.*\\.(ts|tsx|js)$"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
