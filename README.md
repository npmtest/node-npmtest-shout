# npmtest-shout

#### basic test coverage for  [shout (v0.53.0)](https://github.com/erming/shout#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-shout.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-shout) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-shout.svg)](https://travis-ci.org/npmtest/node-npmtest-shout)

#### The self-hosted Web IRC client

[![NPM](https://nodei.co/npm/shout.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/shout)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-shout/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-shout/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-shout/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-shout/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-shout/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-shout/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-shout/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-shout/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-shout/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-shout/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-shout/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-shout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-shout/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-shout/build/test-report.html](https://npmtest.github.io/node-npmtest-shout/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-shout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-shout/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-shout/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-shout/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-shout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-shout/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-shout/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-shout/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mattias Erming"
    },
    "bin": {
        "shout": "index.js"
    },
    "bugs": {
        "url": "https://github.com/erming/shout/issues"
    },
    "dependencies": {
        "bcrypt-nodejs": "0.0.3",
        "cheerio": "^0.17.0",
        "commander": "^2.3.0",
        "event-stream": "^3.1.7",
        "express": "^4.9.5",
        "lodash": "~2.4.1",
        "mkdirp": "^0.5.0",
        "moment": "~2.7.0",
        "read": "^1.0.5",
        "request": "^2.51.0",
        "slate-irc": "~0.7.3",
        "socket.io": "~1.0.6"
    },
    "description": "The self-hosted Web IRC client",
    "devDependencies": {
        "eslint": "^1.5.1",
        "grunt": "~0.4.5",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-uglify": "~0.5.0",
        "grunt-contrib-watch": "^0.6.1",
        "handlebars": "^2.0.0",
        "mocha": "~2.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "13ebfcb3b741759d2475db96107776c81d308ae8",
        "tarball": "https://registry.npmjs.org/shout/-/shout-0.53.0.tgz"
    },
    "gitHead": "baadc3df3534fb22515a8c2ea29218fbbc1228b4",
    "homepage": "https://github.com/erming/shout#readme",
    "keywords": [
        "browser",
        "web",
        "chat",
        "client",
        "irc",
        "server"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "astorije"
        },
        {
            "name": "erming"
        }
    ],
    "name": "shout",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/erming/shout.git"
    },
    "scripts": {
        "build": "grunt",
        "lint": "eslint index.js Gruntfile.js src/ test/ client/ defaults/",
        "start": "node index",
        "test": "HOME=test/fixtures mocha test/**/*.js && npm run lint"
    },
    "version": "0.53.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
