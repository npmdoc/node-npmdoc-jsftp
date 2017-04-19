# npmdoc-jsftp

#### api documentation for  [jsftp (v1.5.5)](https://github.com/sergi/jsftp)  [![npm package](https://img.shields.io/npm/v/npmdoc-jsftp.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jsftp) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jsftp.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jsftp)

#### A sane FTP client implementation for NodeJS

[![NPM](https://nodei.co/npm/jsftp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsftp)

- [https://npmdoc.github.io/node-npmdoc-jsftp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsftp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsftp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsftp/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jsftp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jsftp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sergi Mansilla",
        "url": "http://sergimansilla.com"
    },
    "bugs": {
        "url": "https://github.com/sergi/jsftp/issues"
    },
    "dependencies": {
        "debug": "^2.2.0",
        "ftp-response-parser": "^1.0.1",
        "once": "^1.3.3",
        "parse-listing": "^1.1.3",
        "stream-combiner": "^0.2.2",
        "unorm": "^1.4.1"
    },
    "description": "A sane FTP client implementation for NodeJS",
    "devDependencies": {
        "concat-stream": "^1.5.0",
        "ftp-test-server": "0.0.2",
        "ftpd": "^0.2.15",
        "istanbul": "^0.3.22",
        "mocha": "^1.21.4",
        "mocha-istanbul": "0.2.0",
        "rimraf": "^2.2.8",
        "sinon": "^1.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "3d034569a58221c8ffc67d088688f59d2e995cee",
        "tarball": "https://registry.npmjs.org/jsftp/-/jsftp-1.5.5.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "e26e162e438ae0f1e6815e0ad4aa476a185a5f71",
    "homepage": "https://github.com/sergi/jsftp",
    "id": "jsftp",
    "keywords": [
        "ftp",
        "protocol",
        "files",
        "server",
        "client",
        "async"
    ],
    "license": "MIT",
    "main": "lib/jsftp.js",
    "maintainers": [
        {
            "name": "sergi"
        }
    ],
    "name": "jsftp",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sergi/jsftp.git"
    },
    "scripts": {
        "clean": "rm -rf reports",
        "test": "mocha -R spec -t 5000"
    },
    "version": "1.5.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
