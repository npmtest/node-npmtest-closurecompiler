# npmtest-closurecompiler

#### test coverage for  [closurecompiler (v1.6.1)](https://github.com/dcodeIO/ClosureCompiler.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-closurecompiler.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-closurecompiler) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-closurecompiler.svg)](https://travis-ci.org/npmtest/node-npmtest-closurecompiler)

#### ClosureCompiler.js: Closure Compiler for node.js. The all-round carefree package.

[![NPM](https://nodei.co/npm/closurecompiler.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/closurecompiler)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-closurecompiler/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-closurecompiler/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-closurecompiler/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-closurecompiler/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-closurecompiler/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-closurecompiler/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-closurecompiler/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-closurecompiler/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-closurecompiler/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-closurecompiler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-closurecompiler/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-closurecompiler/build/test-report.html](https://npmtest.github.io/node-npmtest-closurecompiler/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-closurecompiler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-closurecompiler/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-closurecompiler/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-closurecompiler/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-closurecompiler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-closurecompiler/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-closurecompiler/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-closurecompiler/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel Wirtz"
    },
    "bin": {
        "ccjs": "./bin/ccjs"
    },
    "bugs": {
        "url": "https://github.com/dcodeIO/ClosureCompiler.js/issues"
    },
    "contributors": [
        {
            "name": "Feross Aboukhadijeh"
        }
    ],
    "dependencies": {
        "bl": "~0.9.3",
        "closurecompiler-externs": "*",
        "tar": "~2.2.1"
    },
    "description": "ClosureCompiler.js: Closure Compiler for node.js. The all-round carefree package.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "2adde92bc8e89ff6871a11cf01a59e12650a030f",
        "tarball": "https://registry.npmjs.org/closurecompiler/-/closurecompiler-1.6.1.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "96fd199f24eaada9aa67c30164ffc720218f64a4",
    "homepage": "https://github.com/dcodeIO/ClosureCompiler.js#readme",
    "keywords": [
        "closure compiler",
        "closure",
        "compiler",
        "util",
        "utility"
    ],
    "license": "Apache-2.0",
    "main": "ClosureCompiler.js",
    "maintainers": [
        {
            "name": "dcode"
        }
    ],
    "name": "closurecompiler",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dcodeIO/ClosureCompiler.js.git"
    },
    "scripts": {
        "compile": "node bin/ccjs ClosureCompiler.js --externs=node --compilation_level=SIMPLE_OPTIMIZATIONS > ClosureCompiler.min.js",
        "configure": "node scripts/configure.js",
        "install": "npm run-script configure",
        "make": "npm run-script compile && npm test",
        "test": "node tests/test.js",
        "update": "npm run-script configure"
    },
    "version": "1.6.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
