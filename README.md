# npmdoc-requisition

#### api documentation for  requisition (v1.7.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-requisition.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-requisition) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-requisition.svg)](https://travis-ci.org/npmdoc/node-npmdoc-requisition)

#### ES7 async/await ready http client

[![NPM](https://nodei.co/npm/requisition.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/requisition)

- [https://npmdoc.github.io/node-npmdoc-requisition/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-requisition/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-requisition/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-requisition/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-requisition/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-requisition/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "requisition",
    "description": "ES7 async/await ready http client",
    "version": "1.7.0",
    "author": "Jonathan Ong <me@jongleberry.com> (http://jongleberry.com)",
    "license": "MIT",
    "repository": "thenables/requisition",
    "dependencies": {
        "any-promise": "^1.1.0",
        "cookie": "^0.2.3",
        "destroy": "^1.0.3",
        "fs-cp": "^1.2.0",
        "http-errors": "^1.2.7",
        "media-typer": "^0.3.0",
        "memorizer": "^1.0.0",
        "methods": "^1.1.0",
        "mime-types": "^2.0.2",
        "mz": "^2.1.0",
        "parse-link-header": "^0.4.1",
        "statuses": "^1.2.0",
        "stream-to-array": "^2.0.2",
        "temp-path": "^1.0.0",
        "type-is": "^1.5.2"
    },
    "devDependencies": {
        "basic-auth": "^1.0.0",
        "bluebird": "^3.1.1",
        "body-parser": "^1.10.0",
        "concat-stream": "^1.4.7",
        "cookie-parser": "^1.4.1",
        "express": "^4.9.8",
        "istanbul": "^0.4.2",
        "mocha": "^2.0.0"
    },
    "scripts": {
        "test": "mocha --bail",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter dot"
    },
    "keywords": [
        "request",
        "promise",
        "http",
        "https",
        "client"
    ],
    "main": "lib",
    "files": [
        "lib"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
