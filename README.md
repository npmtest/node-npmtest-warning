# npmtest-warning

#### basic test coverage for  [warning (v3.0.0)](https://github.com/BerkeleyTrue/warning)  [![npm package](https://img.shields.io/npm/v/npmtest-warning.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-warning) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-warning.svg)](https://travis-ci.org/npmtest/node-npmtest-warning)

#### A mirror of Facebook's Warning

[![NPM](https://nodei.co/npm/warning.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/warning)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-warning/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-warning/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-warning/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-warning/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-warning/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-warning/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-warning/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-warning/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-warning/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-warning/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-warning/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-warning/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-warning/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-warning/build/test-report.html](https://npmtest.github.io/node-npmtest-warning/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-warning/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-warning/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-warning/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-warning/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-warning/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-warning/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-warning/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-warning/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Berkeley Martinez",
        "url": "http://www.freecodecamp.com"
    },
    "browser": "browser.js",
    "browserify": {
        "transform": [
            "loose-envify"
        ]
    },
    "bugs": {
        "url": "https://github.com/BerkeleyTrue/warning/issues"
    },
    "dependencies": {
        "loose-envify": "^1.0.0"
    },
    "description": "A mirror of Facebook's Warning",
    "devDependencies": {
        "browserify": "^11.0.1",
        "tap": "^1.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "32e5377cb572de4ab04753bdf8821c01ed605b7c",
        "tarball": "https://registry.npmjs.org/warning/-/warning-3.0.0.tgz"
    },
    "files": [
        "browser.js",
        "warning.js"
    ],
    "gitHead": "6ef2da6b3da76eb6fcc735eaa52160fec2ed6078",
    "homepage": "https://github.com/BerkeleyTrue/warning",
    "keywords": [
        "warning",
        "facebook",
        "react",
        "invariant"
    ],
    "license": "BSD-3-Clause",
    "main": "warning.js",
    "maintainers": [
        {
            "name": "berkeleytrue"
        }
    ],
    "name": "warning",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/BerkeleyTrue/warning.git"
    },
    "scripts": {
        "test": "NODE_ENV=production tap test/*.js && NODE_ENV=development tap test/*.js"
    },
    "version": "3.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
