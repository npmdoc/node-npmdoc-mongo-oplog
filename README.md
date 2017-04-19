# npmdoc-mongo-oplog

#### api documentation for  [mongo-oplog (v2.0.2)](https://github.com/cayasso/mongo-oplog)  [![npm package](https://img.shields.io/npm/v/npmdoc-mongo-oplog.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mongo-oplog) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mongo-oplog.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mongo-oplog)

#### Watch mongodb oplog in a simple way

[![NPM](https://nodei.co/npm/mongo-oplog.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mongo-oplog)

- [https://npmdoc.github.io/node-npmdoc-mongo-oplog/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mongo-oplog/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mongo-oplog/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mongo-oplog/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mongo-oplog/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mongo-oplog/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Brumley"
    },
    "bugs": {
        "url": "https://github.com/cayasso/mongo-oplog/issues"
    },
    "dependencies": {
        "babel-polyfill": "^6.20.0",
        "debug": "2.3.x",
        "eventemitter3": "^2.0.2",
        "mongodb": "~2.2.x"
    },
    "description": "Watch mongodb oplog in a simple way",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-core": "^6.20.0",
        "babel-loader": "^6.2.9",
        "babel-plugin-syntax-async-functions": "^6.13.0",
        "babel-plugin-transform-async-to-generator": "^6.16.0",
        "babel-plugin-transform-es2015-destructuring": "^6.19.0",
        "babel-plugin-transform-object-rest-spread": "^6.20.2",
        "babel-plugin-transform-regenerator": "^6.20.0",
        "babel-plugin-transform-runtime": "^6.15.0",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-stage-0": "^6.16.0",
        "mocha": "*",
        "pre-commit": "1.2.0",
        "should": "^11.1.1",
        "xo": "^0.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "e95510215a980a97735142219ca0e1b94ea6ad74",
        "tarball": "https://registry.npmjs.org/mongo-oplog/-/mongo-oplog-2.0.2.tgz"
    },
    "gitHead": "aefaa625b7b764b3513fecaefe3a1059eb9d7072",
    "homepage": "https://github.com/cayasso/mongo-oplog",
    "keywords": [
        "data",
        "mongo",
        "mongodb",
        "watcher",
        "live",
        "oplog",
        "cursor"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "cayasso"
        }
    ],
    "name": "mongo-oplog",
    "optionalDependencies": {},
    "pre-commit": [
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/cayasso/mongo-oplog.git"
    },
    "scripts": {
        "build": "npm run clean && ./node_modules/.bin/babel src -d lib",
        "clean": "rm -rf lib/",
        "prepublish": "npm run build",
        "test": "xo && mocha"
    },
    "version": "2.0.2",
    "xo": {
        "semicolon": false,
        "esnext": true,
        "space": 2,
        "ignores": [
            "test/**"
        ],
        "rules": {
            "curly": 0,
            "new-cap": 0,
            "no-unused-vars": 0,
            "object-curly-spacing": 0,
            "no-unused-expressions": 0,
            "promise/param-names": 0,
            "import/no-unassigned-import": 0,
            "no-negated-condition": 0
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
