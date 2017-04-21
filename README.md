# npmtest-browser-repl

#### basic test coverage for  browser-repl (v0.4.0)  [![npm package](https://img.shields.io/npm/v/npmtest-browser-repl.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-browser-repl) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-browser-repl.svg)](https://travis-ci.org/npmtest/node-npmtest-browser-repl)

#### CLI utility to set up a remote browser repl

[![NPM](https://nodei.co/npm/browser-repl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/browser-repl)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-browser-repl/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-browser-repl/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-browser-repl/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-browser-repl/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-browser-repl/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-browser-repl/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-browser-repl/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-browser-repl/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-browser-repl/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-browser-repl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-browser-repl/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-browser-repl/build/test-report.html](https://npmtest.github.io/node-npmtest-browser-repl/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-browser-repl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-browser-repl/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-browser-repl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-browser-repl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-browser-repl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-browser-repl/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-browser-repl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-browser-repl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "browser-repl",
    "version": "0.4.0",
    "description": "CLI utility to set up a remote browser repl",
    "dependencies": {
        "array-map": "0.0.0",
        "express": "3.4.8",
        "foreach": "2.0.4",
        "minimist": "0.0.7",
        "ngrok": "0.1.99",
        "socket.io": "1.3.5",
        "socket.io-client": "1.3.5",
        "to-array": "0.1.4",
        "util-inspect": "0.1.8",
        "wd": "0.3.11"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/Automattic/browser-repl.git"
    },
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/Automattic/browser-repl/issues"
    },
    "bin": {
        "repl": "./repl.js"
    },
    "scripts": {
        "prepublish": "make build"
    },
    "devDependencies": {
        "browserify": "8.1.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
