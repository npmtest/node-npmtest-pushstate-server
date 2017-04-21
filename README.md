# npmtest-pushstate-server

#### basic test coverage for  pushstate-server (v3.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-pushstate-server.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pushstate-server) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pushstate-server.svg)](https://travis-ci.org/npmtest/node-npmtest-pushstate-server)

#### Static file server that works with HTML5 Pushstate.

[![NPM](https://nodei.co/npm/pushstate-server.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pushstate-server)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pushstate-server/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pushstate-server/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pushstate-server/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pushstate-server/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pushstate-server/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pushstate-server/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pushstate-server/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pushstate-server/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pushstate-server/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pushstate-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pushstate-server/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pushstate-server/build/test-report.html](https://npmtest.github.io/node-npmtest-pushstate-server/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pushstate-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pushstate-server/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pushstate-server/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pushstate-server/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pushstate-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pushstate-server/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pushstate-server/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pushstate-server/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pushstate-server",
    "version": "3.0.0",
    "description": "Static file server that works with HTML5 Pushstate.",
    "main": "index.js",
    "scripts": {
        "test": "npm run format && npm run test-runner",
        "test-runner": "tape test/index.js | tap-format-spec",
        "format": "prettier --write \"index.js\" \"test/index.js\""
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/scottcorgan/pushstate-server.git"
    },
    "keywords": [
        "pushstate",
        "html5",
        "static",
        "server"
    ],
    "author": "Scott Corgan",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/scottcorgan/pushstate-server/issues"
    },
    "dependencies": {
        "compression": "1.6.2",
        "connect": "3.6.0",
        "connect-static-file": "1.1.2",
        "serve-static": "1.12.0"
    },
    "devDependencies": {
        "@tap-format/spec": "0.2.0",
        "got": "6.7.1",
        "prettier": "0.20.0",
        "tape": "4.6.3"
    },
    "bin": {
        "pushstate-server": "./bin/pushstate-server"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
