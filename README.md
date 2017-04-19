# npmdoc-browserify-middleware

#### api documentation for  [browserify-middleware (v7.1.0)](https://github.com/ForbesLindesay/browserify-middleware#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-browserify-middleware.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-browserify-middleware) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-browserify-middleware.svg)](https://travis-ci.org/npmdoc/node-npmdoc-browserify-middleware)

#### express middleware for browserify v2

[![NPM](https://nodei.co/npm/browserify-middleware.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/browserify-middleware)

- [https://npmdoc.github.io/node-npmdoc-browserify-middleware/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-browserify-middleware/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-browserify-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-browserify-middleware/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-browserify-middleware/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-browserify-middleware/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "ForbesLindesay"
    },
    "bugs": {
        "url": "https://github.com/ForbesLindesay/browserify-middleware/issues"
    },
    "dependencies": {
        "browserify": "^13.1.0",
        "ms": "^0.7.1",
        "prepare-response": "^1.1.2",
        "promise": "^7.0.3",
        "uglify-js": "^2.7.3",
        "watchify": "^3.3.0"
    },
    "description": "express middleware for browserify v2",
    "devDependencies": {
        "concat-stream": "*",
        "coveralls": "^2.11.2",
        "express": "*",
        "hyperquest": "*",
        "istanbul": "^0.3.5",
        "mocha": "*",
        "require-test": "1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "42766809c748fb3ebdee497cb5b3de466870aa05",
        "tarball": "https://registry.npmjs.org/browserify-middleware/-/browserify-middleware-7.1.0.tgz"
    },
    "gitHead": "99b43cf294f117463e20320e15eb5bc96d3b9c4e",
    "homepage": "https://github.com/ForbesLindesay/browserify-middleware#readme",
    "keywords": [
        "browserify",
        "middleware",
        "express",
        "connect"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "forbeslindesay"
        },
        {
            "name": "allain"
        },
        {
            "name": "scottbrady"
        }
    ],
    "name": "browserify-middleware",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ForbesLindesay/browserify-middleware.git"
    },
    "scripts": {
        "coverage": "istanbul cover node_modules/mocha/bin/_mocha -- -t 7000",
        "coveralls": "npm run coverage && cat ./coverage/lcov.info | coveralls",
        "test": "mocha -R spec -t 7000",
        "test:perf": "mocha -R spec -t 7000"
    },
    "version": "7.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
