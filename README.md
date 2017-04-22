# npmdoc-path-to-regexp

#### api documentation for  [path-to-regexp (v1.7.0)](https://github.com/pillarjs/path-to-regexp#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-path-to-regexp.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-path-to-regexp) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-path-to-regexp.svg)](https://travis-ci.org/npmdoc/node-npmdoc-path-to-regexp)

#### Express style path to RegExp utility

[![NPM](https://nodei.co/npm/path-to-regexp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/path-to-regexp)

- [https://npmdoc.github.io/node-npmdoc-path-to-regexp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-path-to-regexp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-path-to-regexp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-path-to-regexp/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-path-to-regexp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-path-to-regexp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/pillarjs/path-to-regexp/issues"
    },
    "component": {
        "scripts": {
            "path-to-regexp": "index.js"
        }
    },
    "dependencies": {
        "isarray": "0.0.1"
    },
    "description": "Express style path to RegExp utility",
    "devDependencies": {
        "chai": "^2.3.0",
        "istanbul": "~0.3.0",
        "mocha": "~2.2.4",
        "standard": "~3.7.3",
        "ts-node": "^0.5.5",
        "typescript": "^1.8.7",
        "typings": "^1.0.4"
    },
    "directories": {},
    "dist": {
        "shasum": "59fde0f435badacba103a84e9d3bc64e96b9937d",
        "tarball": "https://registry.npmjs.org/path-to-regexp/-/path-to-regexp-1.7.0.tgz"
    },
    "files": [
        "index.js",
        "index.d.ts",
        "LICENSE"
    ],
    "gitHead": "a99ec3c149e8c1d91fa533aa54d3ee7e34449bb3",
    "homepage": "https://github.com/pillarjs/path-to-regexp#readme",
    "keywords": [
        "express",
        "regexp",
        "route",
        "routing"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "amasad"
        },
        {
            "name": "anthonyshort"
        },
        {
            "name": "blakeembrey"
        },
        {
            "name": "calvinfo"
        },
        {
            "name": "clintwood"
        },
        {
            "name": "coreh"
        },
        {
            "name": "cristiandouce"
        },
        {
            "name": "defunctzombie"
        },
        {
            "name": "dfcreative"
        },
        {
            "name": "dominicbarnes"
        },
        {
            "name": "dougwilson"
        },
        {
            "name": "forbeslindesay"
        },
        {
            "name": "ianstormtaylor"
        },
        {
            "name": "jonathanong"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "juliangruber"
        },
        {
            "name": "kelonye"
        },
        {
            "name": "mattmueller"
        },
        {
            "name": "nami-doc"
        },
        {
            "name": "queckezz"
        },
        {
            "name": "rauchg"
        },
        {
            "name": "retrofox"
        },
        {
            "name": "stagas"
        },
        {
            "name": "stephenmathieson"
        },
        {
            "name": "swatinem"
        },
        {
            "name": "thehydroimpulse"
        },
        {
            "name": "timaschew"
        },
        {
            "name": "timoxley"
        },
        {
            "name": "tjholowaychuk"
        },
        {
            "name": "tootallnate"
        },
        {
            "name": "trevorgerhardt"
        },
        {
            "name": "yields"
        }
    ],
    "name": "path-to-regexp",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pillarjs/path-to-regexp.git"
    },
    "scripts": {
        "lint": "standard",
        "prepublish": "typings install",
        "test": "npm run lint && npm run test-cov",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --require ts-node/register -R spec test.ts",
        "test-spec": "mocha --require ts-node/register -R spec --bail test.ts"
    },
    "typings": "index.d.ts",
    "version": "1.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
