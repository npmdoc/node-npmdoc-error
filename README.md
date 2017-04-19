# npmdoc-error

#### api documentation for  [error (v7.0.2)](https://github.com/Raynos/error)  [![npm package](https://img.shields.io/npm/v/npmdoc-error.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-error) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-error.svg)](https://travis-ci.org/npmdoc/node-npmdoc-error)

#### Custom errors

[![NPM](https://nodei.co/npm/error.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/error)

- [https://npmdoc.github.io/node-npmdoc-error/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-error/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-error/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-error/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-error/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-error/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Raynos"
    },
    "bugs": {
        "url": "https://github.com/Raynos/error/issues"
    },
    "contributors": [
        {
            "name": "Raynos"
        }
    ],
    "dependencies": {
        "string-template": "~0.2.1",
        "xtend": "~4.0.0"
    },
    "description": "Custom errors",
    "devDependencies": {
        "istanbul": "0.3.13",
        "tape": "^3.5.0",
        "uber-standard": "3.6.4"
    },
    "directories": {},
    "dist": {
        "shasum": "a5f75fff4d9926126ddac0ea5dc38e689153cb02",
        "tarball": "https://registry.npmjs.org/error/-/error-7.0.2.tgz"
    },
    "gitHead": "997d4df1bc9c748bf31e61622e922c10af0979c2",
    "homepage": "https://github.com/Raynos/error",
    "keywords": [],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/Raynos/error/raw/master/LICENSE"
        }
    ],
    "main": "index",
    "maintainers": [
        {
            "name": "raynos"
        },
        {
            "name": "jcorbin"
        }
    ],
    "name": "error",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Raynos/error.git"
    },
    "scripts": {
        "cover": "istanbul cover --report none --print detail ./test/index.js",
        "lint": "standard -v .",
        "test": "npm run lint && node test/index.js",
        "test-browser": "testem-browser ./test/browser/index.js",
        "testem": "testem-both -b=./test/browser/index.js",
        "travis-test": "istanbul cover ./test/index.js && ((cat coverage/lcov.info | coveralls) || exit 0)",
        "view-cover": "istanbul report html && google-chrome ./coverage/index.html"
    },
    "testling": {
        "files": "test/index.js",
        "browsers": [
            "ie/8..latest",
            "firefox/16..latest",
            "firefox/nightly",
            "chrome/22..latest",
            "chrome/canary",
            "opera/12..latest",
            "opera/next",
            "safari/5.1..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest",
            "android-browser/4.2..latest"
        ]
    },
    "version": "7.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
