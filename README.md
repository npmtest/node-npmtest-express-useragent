# npmtest-express-useragent

test coverage for  [express-useragent (v1.0.7)](https://github.com/biggora/express-useragent/)  [![npm package](https://img.shields.io/npm/v/npmtest-express-useragent.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-useragent) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-useragent.svg)](https://travis-ci.org/npmtest/node-npmtest-express-useragent)
#### ExpressJS/Connect/TrinteJS user-agent middleware exposing

[![NPM](https://nodei.co/npm/express-useragent.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-useragent)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-useragent/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-useragent/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-useragent/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-useragent/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-useragent/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-useragent/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-useragent/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-useragent/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-useragent/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-useragent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-useragent/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-useragent/build/test-report.html](https://npmtest.github.io/node-npmtest-express-useragent/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-useragent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-useragent/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-useragent/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-useragent/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-useragent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-useragent/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-useragent/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-useragent/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alexey Gordeyev",
        "url": "https://github.com/biggora"
    },
    "bugs": {
        "url": "https://github.com/biggora/express-useragent/issues"
    },
    "contributors": [
        {
            "name": "Kacper Glowacki",
            "url": "https://github.com/kacperus"
        },
        {
            "name": "elisee",
            "url": "https://github.com/elisee"
        },
        {
            "name": "Bitdeli Chef",
            "url": "https://github.com/bitdeli-chef"
        },
        {
            "name": "Nicolas Tobo",
            "url": "https://github.com/nicolastobo"
        },
        {
            "name": "Samy Pess�",
            "url": "https://github.com/SamyPesse"
        },
        {
            "name": "Artem Nezvigin",
            "url": "https://github.com/artnez"
        },
        {
            "name": "Josh Dickson",
            "url": "https://github.com/joshdickson40"
        }
    ],
    "dependencies": {},
    "description": "ExpressJS/Connect/TrinteJS user-agent middleware exposing",
    "devDependencies": {
        "bower": "*",
        "express": ">= 3.0.0",
        "grunt": "*",
        "grunt-contrib-clean": "*",
        "grunt-contrib-uglify": "*",
        "jshint": "*",
        "load-grunt-tasks": "^3.2.0",
        "nodeunit": "*"
    },
    "directories": {
        "lib": "lib",
        "test": "test"
    },
    "dist": {
        "shasum": "153de647e5a5d05c4ec1b4172794a46bc0d07991",
        "tarball": "https://registry.npmjs.org/express-useragent/-/express-useragent-1.0.7.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "c25499f977266ebaeb6738cf76280077dc672e9a",
    "homepage": "https://github.com/biggora/express-useragent/",
    "keywords": [
        "useragent",
        "connect",
        "express",
        "trinte",
        "browser",
        "compound",
        "middleware"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "biggora"
        }
    ],
    "name": "express-useragent",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/biggora/express-useragent.git"
    },
    "scripts": {
        "build": "grunt build",
        "express": "node test/express.js",
        "http": "node test/http.js",
        "lint": "make lint",
        "test": "nodeunit test/browsers.js test/bots_test.js"
    },
    "version": "1.0.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
