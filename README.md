# npmtest-koa-router

#### basic test coverage for  [koa-router (v7.1.1)](https://github.com/alexmingoia/koa-router#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-koa-router.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-koa-router) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-koa-router.svg)](https://travis-ci.org/npmtest/node-npmtest-koa-router)

#### Router middleware for koa. Provides RESTful resource routing.

[![NPM](https://nodei.co/npm/koa-router.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-router)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-koa-router/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-router/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-koa-router/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-koa-router/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-koa-router/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-koa-router/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-koa-router/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-koa-router/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-koa-router/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-koa-router/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-koa-router/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-router/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-koa-router/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-koa-router/build/test-report.html](https://npmtest.github.io/node-npmtest-koa-router/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-koa-router/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-koa-router/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-koa-router/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-router/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-router/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-router/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-koa-router/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-koa-router/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alex Mingoia"
    },
    "bugs": {
        "url": "https://github.com/alexmingoia/koa-router/issues"
    },
    "dependencies": {
        "debug": "^2.2.0",
        "http-errors": "^1.3.1",
        "koa-compose": "^3.0.0",
        "methods": "^1.0.1",
        "path-to-regexp": "^1.1.1"
    },
    "description": "Router middleware for koa. Provides RESTful resource routing.",
    "devDependencies": {
        "expect.js": "^0.3.1",
        "gulp": "^3.8.11",
        "gulp-mocha": "^2.0.0",
        "jsdoc-to-markdown": "^1.1.1",
        "koa": "^2.0.0-alpha.3",
        "mocha": "^2.0.1",
        "should": "^6.0.3",
        "supertest": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "38cce6b1381fada18cfa47a3b3323e995ca231cf",
        "tarball": "https://registry.npmjs.org/koa-router/-/koa-router-7.1.1.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "files": [
        "lib"
    ],
    "gitHead": "b378984f0466c4cb1dbe25f874ba3bf46594e634",
    "homepage": "https://github.com/alexmingoia/koa-router#readme",
    "keywords": [
        "koa",
        "middleware",
        "router",
        "route"
    ],
    "license": "MIT",
    "main": "lib/router.js",
    "maintainers": [
        {
            "name": "amingoia"
        }
    ],
    "name": "koa-router",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/alexmingoia/koa-router.git"
    },
    "scripts": {
        "docs": "NODE_ENV=test node node_modules/gulp/bin/gulp.js docs",
        "test": "NODE_ENV=test node node_modules/gulp/bin/gulp.js test"
    },
    "version": "7.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
