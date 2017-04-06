# api documentation for  [error (v7.0.2)](https://github.com/Raynos/error)  [![npm package](https://img.shields.io/npm/v/npmdoc-error.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-error) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-error.svg)](https://travis-ci.org/npmdoc/node-npmdoc-error)
#### Custom errors

[![NPM](https://nodei.co/npm/error.png?downloads=true)](https://www.npmjs.com/package/error)

[![apidoc](https://npmdoc.github.io/node-npmdoc-error/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-error_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-error/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-error/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-error/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Raynos",
        "email": "raynos2@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/Raynos/error/issues",
        "email": "raynos2@gmail.com"
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
            "name": "raynos",
            "email": "raynos2@gmail.com"
        },
        {
            "name": "jcorbin",
            "email": "jcorbin@wunjo.org"
        }
    ],
    "name": "error",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module error](#apidoc.module.error)



# <a name="apidoc.module.error"></a>[module error](#apidoc.module.error)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
