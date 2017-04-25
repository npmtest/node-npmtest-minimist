# npmtest-minimist

#### basic test coverage for  [minimist (v1.2.0)](https://github.com/substack/minimist)  [![npm package](https://img.shields.io/npm/v/npmtest-minimist.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-minimist) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-minimist.svg)](https://travis-ci.org/npmtest/node-npmtest-minimist)

#### parse argument options

[![NPM](https://nodei.co/npm/minimist.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/minimist)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-minimist/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-minimist/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-minimist/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-minimist/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-minimist/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-minimist/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-minimist/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-minimist/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-minimist/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-minimist/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-minimist/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-minimist/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-minimist/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-minimist/build/test-report.html](https://npmtest.github.io/node-npmtest-minimist/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-minimist/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-minimist/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-minimist/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-minimist/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-minimist/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-minimist/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-minimist/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-minimist/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "bugs": {
        "url": "https://github.com/substack/minimist/issues"
    },
    "dependencies": {},
    "description": "parse argument options",
    "devDependencies": {
        "covert": "^1.0.0",
        "tap": "~0.4.0",
        "tape": "^3.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a35008b20f41383eec1fb914f4cd5df79a264284",
        "tarball": "https://registry.npmjs.org/minimist/-/minimist-1.2.0.tgz"
    },
    "gitHead": "dc624482fcfec5bc669c68cdb861f00573ed4e64",
    "homepage": "https://github.com/substack/minimist",
    "keywords": [
        "argv",
        "getopt",
        "parser",
        "optimist"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "substack"
        }
    ],
    "name": "minimist",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/minimist.git"
    },
    "scripts": {
        "coverage": "covert test/*.js",
        "test": "tap test/*.js"
    },
    "testling": {
        "files": "test/*.js",
        "browsers": [
            "ie/6..latest",
            "ff/5",
            "firefox/latest",
            "chrome/10",
            "chrome/latest",
            "safari/5.1",
            "safari/latest",
            "opera/12"
        ]
    },
    "version": "1.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
