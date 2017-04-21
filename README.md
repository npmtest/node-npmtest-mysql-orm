# npmtest-mysql-orm

#### basic test coverage for  [mysql-orm (v0.0.8)](https://github.com/battlesnake/node-mysql-orm)  [![npm package](https://img.shields.io/npm/v/npmtest-mysql-orm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mysql-orm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mysql-orm.svg)](https://travis-ci.org/npmtest/node-npmtest-mysql-orm)

#### ORM frontend for MySQL, uses JSON schema to define tables and relationships.  This supports automatic table re-generation with indexes, default values, foreign keys, reference options, query logging and more.

[![NPM](https://nodei.co/npm/mysql-orm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mysql-orm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mysql-orm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mysql-orm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mysql-orm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mysql-orm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mysql-orm/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mysql-orm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mysql-orm/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mysql-orm/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mysql-orm/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mysql-orm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mysql-orm/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mysql-orm/build/test-report.html](https://npmtest.github.io/node-npmtest-mysql-orm/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mysql-orm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mysql-orm/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mysql-orm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mysql-orm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mysql-orm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mysql-orm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mysql-orm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mysql-orm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mark K Cowan"
    },
    "bugs": {
        "url": "https://github.com/battlesnake/node-mysql-orm/issues"
    },
    "contributors": [
        {
            "name": "Mark K Cowan"
        }
    ],
    "dependencies": {
        "async": "*",
        "cli-color": "*",
        "mysql": "*",
        "underscore": "*"
    },
    "description": "ORM frontend for MySQL, uses JSON schema to define tables and relationships.  This supports automatic table re-generation with indexes, default values, foreign keys, reference options, query logging and more.",
    "devDependencies": {
        "read": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "77394751a8c6cd84fb6a60577235edf79d943d36",
        "tarball": "https://registry.npmjs.org/mysql-orm/-/mysql-orm-0.0.8.tgz"
    },
    "engines": {
        "node": "*"
    },
    "homepage": "https://github.com/battlesnake/node-mysql-orm",
    "keywords": [
        "mysql",
        "orm",
        "object schema",
        "object relational mapping",
        "dry",
        "rest",
        "crud"
    ],
    "license": "GPL2",
    "main": "index.js",
    "maintainers": [
        {
            "name": "battlesnake"
        }
    ],
    "name": "mysql-orm",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/battlesnake/node-mysql-orm.git"
    },
    "scripts": {
        "test": "./run-tests.js testuser testpwd testdb31415926"
    },
    "version": "0.0.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
