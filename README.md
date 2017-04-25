# npmtest-node-etcd

#### basic test coverage for  [node-etcd (v5.0.3)](https://github.com/stianeikeland/node-etcd#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-node-etcd.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-etcd) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-etcd.svg)](https://travis-ci.org/npmtest/node-npmtest-node-etcd)

#### etcd library for node.js (etcd v2 api)

[![NPM](https://nodei.co/npm/node-etcd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-etcd)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-etcd/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-etcd/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-etcd/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-etcd/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-etcd/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-node-etcd/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-node-etcd/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-etcd/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-etcd/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-etcd/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-etcd/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-etcd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-etcd/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-etcd/build/test-report.html](https://npmtest.github.io/node-npmtest-node-etcd/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-etcd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-etcd/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-etcd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-etcd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-etcd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-etcd/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-etcd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-etcd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/stianeikeland/node-etcd/issues"
    },
    "dependencies": {
        "deasync": "0.1.7",
        "request": "2.60.0",
        "underscore": "1.8.2",
        "url-parse": "1.0.5"
    },
    "description": "etcd library for node.js (etcd v2 api)",
    "devDependencies": {
        "coffee-script": "1.9.1",
        "mocha": "2.1.0",
        "nock": "2.17.0",
        "should": "5.0.1",
        "simple-mock": "0.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8b616da4689b5456ca686b24294214330c471bf8",
        "tarball": "https://registry.npmjs.org/node-etcd/-/node-etcd-5.0.3.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "fea875005d654e06aba2e1374085d7a57448420c",
    "homepage": "https://github.com/stianeikeland/node-etcd#readme",
    "keywords": [
        "etcd",
        "raft"
    ],
    "licenses": [
        {
            "type": "BSD 3-Clause",
            "url": "http://opensource.org/licenses/BSD-3-Clause"
        }
    ],
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "stiane"
        }
    ],
    "name": "node-etcd",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/stianeikeland/node-etcd.git"
    },
    "scripts": {
        "build": "coffee --bare --compile --output lib/ src/*.coffee",
        "postpublish": "rm -rf lib",
        "prepublish": "coffee --bare --compile --output lib/ src/*.coffee",
        "test": "mocha --compilers coffee:coffee-script/register test/",
        "watch": "mocha --compilers coffee:coffee-script/register --watch"
    },
    "version": "5.0.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
