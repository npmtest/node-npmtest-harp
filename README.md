# npmtest-harp

#### basic test coverage for  [harp (v0.23.0)](http://harpjs.com)  [![npm package](https://img.shields.io/npm/v/npmtest-harp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-harp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-harp.svg)](https://travis-ci.org/npmtest/node-npmtest-harp)

#### Static web server with built in preprocessing

[![NPM](https://nodei.co/npm/harp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/harp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-harp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-harp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-harp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-harp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-harp/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-harp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-harp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-harp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-harp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-harp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-harp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-harp/build/test-report.html](https://npmtest.github.io/node-npmtest-harp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-harp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-harp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-harp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-harp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-harp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-harp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-harp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-harp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brock Whitten"
    },
    "bin": {
        "harp": "./bin/harp"
    },
    "bugs": {
        "url": "http://github.com/sintaxi/harp/issues"
    },
    "contributors": [
        {
            "name": "Brock Whitten"
        },
        {
            "name": "Rob Ellis"
        },
        {
            "name": "Jorge Pedret"
        },
        {
            "name": "Michael Brooks"
        },
        {
            "name": "Tommy-Carlos Williams"
        },
        {
            "name": "Darryl Pogue"
        },
        {
            "name": "Boris Mann"
        },
        {
            "name": "Kenneth Ormandy"
        },
        {
            "name": "Keith Yao"
        },
        {
            "name": "Eric Drechsel"
        },
        {
            "name": "Andrew Hobden"
        },
        {
            "name": "Max Melentiev"
        },
        {
            "name": "Remy Sharp"
        },
        {
            "name": "Zeke Sikelianos"
        },
        {
            "name": "Marc Knaup"
        },
        {
            "name": "Jurgen Van de Moere"
        }
    ],
    "dependencies": {
        "async": "0.2.9",
        "commander": "2.0.0",
        "connect": "2.30.2",
        "download-github-repo": "0.1.3",
        "envy-json": "0.2.1",
        "escape-html": "1.0.3",
        "fs-extra": "0.18.2",
        "mime": "1.2.11",
        "parseurl": "1.3.0",
        "pause": "0.1.0",
        "send": "0.13.0",
        "terraform": "1.3.0"
    },
    "description": "Static web server with built in preprocessing",
    "devDependencies": {
        "cheerio": "0.19.0",
        "mocha": "1.21.5",
        "nixt": "0.4.1",
        "request": "2.61.0",
        "should": "3.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "5db8493f8074cdf9bd478d336de7328729f3ff0b",
        "tarball": "https://registry.npmjs.org/harp/-/harp-0.23.0.tgz"
    },
    "engines": {
        "node": ">=0.12"
    },
    "gitHead": "7c0e02a7a150f713e0bdae316e889741aeaad83c",
    "homepage": "http://harpjs.com",
    "keywords": [
        "static web server",
        "static site generator",
        "sass",
        "less",
        "stylus",
        "markdown",
        "jade",
        "ejs",
        "coffeescript"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "kennethormandy"
        },
        {
            "name": "sintaxi"
        }
    ],
    "name": "harp",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sintaxi/harp.git"
    },
    "scripts": {
        "test": "mocha --reporter spec -t 8000"
    },
    "version": "0.23.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
