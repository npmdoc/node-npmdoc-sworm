# npmdoc-sworm

#### api documentation for  [sworm (v3.6.0)](https://github.com/featurist/sworm)  [![npm package](https://img.shields.io/npm/v/npmdoc-sworm.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sworm) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sworm.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sworm)

#### a lightweight write-only ORM for MSSQL, MySQL, PostgreSQL, Oracle, Sqlite 3

[![NPM](https://nodei.co/npm/sworm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sworm)

- [https://npmdoc.github.io/node-npmdoc-sworm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sworm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sworm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sworm/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sworm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sworm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sworm",
    "version": "3.6.0",
    "description": "a lightweight write-only ORM for MSSQL, MySQL, PostgreSQL, Oracle, Sqlite 3",
    "main": "index.js",
    "directories": {
        "test": "test"
    },
    "dependencies": {
        "cooperative": "1.1.0",
        "debug": "2.2.0",
        "randomstring": "1.1.5",
        "underscore": "1.8.3"
    },
    "devDependencies": {
        "chai": "3.5.0",
        "chai-as-promised": "5.3.0",
        "electron": "1.6.2",
        "electron-mocha": "3.3.0",
        "es6-promise": "3.2.1",
        "fs-promise": "0.5.0",
        "mocha": "3.2.0",
        "mssql": "3.3.0",
        "mysql": "2.11.1",
        "pg": "6.1.0",
        "sqlite3": "3.1.8"
    },
    "scripts": {
        "test": "mocha && electron-mocha --renderer test/browser"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/featurist/sworm.git"
    },
    "keywords": [
        "activerecord",
        "database",
        "postgres",
        "postgresql",
        "mysql",
        "orm",
        "mssql",
        "sqlserver",
        "sql",
        "server"
    ],
    "author": "Tim Macfarlane <timmacfarlane@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/featurist/sworm/issues"
    },
    "homepage": "https://github.com/featurist/sworm"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
