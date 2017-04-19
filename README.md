# npmdoc-express-xml-bodyparser

#### api documentation for  [express-xml-bodyparser (v0.3.0)](https://github.com/macedigital/express-xml-bodyparser)  [![npm package](https://img.shields.io/npm/v/npmdoc-express-xml-bodyparser.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-express-xml-bodyparser) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-express-xml-bodyparser.svg)](https://travis-ci.org/npmdoc/node-npmdoc-express-xml-bodyparser)

#### Simple XML body parser connect/express middleware

[![NPM](https://nodei.co/npm/express-xml-bodyparser.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-xml-bodyparser)

- [https://npmdoc.github.io/node-npmdoc-express-xml-bodyparser/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-xml-bodyparser/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-xml-bodyparser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-xml-bodyparser/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-express-xml-bodyparser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-express-xml-bodyparser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matthias Adler",
        "url": "http://matthiasadler.info/"
    },
    "bugs": {
        "url": "https://github.com/macedigital/express-xml-bodyparser/issues"
    },
    "contributors": [
        {
            "name": "asperling",
            "url": "https://github.com/asperling"
        },
        {
            "name": "Pavel Strashkin",
            "url": "https://github.com/xaka"
        },
        {
            "name": "ophentis",
            "url": "https://github.com/ophentis"
        },
        {
            "name": "fiznool",
            "url": "https://github.com/fiznool"
        },
        {
            "name": "dirksen",
            "url": "https://github.com/dirksen"
        }
    ],
    "dependencies": {
        "xml2js": "^0.4.11"
    },
    "description": "Simple XML body parser connect/express middleware",
    "devDependencies": {
        "express": "^3.18",
        "istanbul": "^0.3.7",
        "mocha": "^2.2.5",
        "supertest": "^1.0.1"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "b1f5a98adf6c6e412c4ccba634234b82945c62be",
        "tarball": "https://registry.npmjs.org/express-xml-bodyparser/-/express-xml-bodyparser-0.3.0.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "files": [
        "LICENSE",
        "README.md",
        "index.js",
        "lib/"
    ],
    "gitHead": "acd00116617ff183b297a1214b4252a0b68c2e6c",
    "homepage": "https://github.com/macedigital/express-xml-bodyparser",
    "keywords": [
        "xml",
        "json",
        "middleware",
        "parser",
        "express"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "macedigital"
        }
    ],
    "name": "express-xml-bodyparser",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/macedigital/express-xml-bodyparser.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --check-leaks --bail test/ 2> /dev/null",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/ 2> /dev/null",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/ 2> /dev/null"
    },
    "version": "0.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
