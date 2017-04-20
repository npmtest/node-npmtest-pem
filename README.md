# npmtest-pem

#### basic test coverage for  pem (v1.9.4)  [![npm package](https://img.shields.io/npm/v/npmtest-pem.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pem) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pem.svg)](https://travis-ci.org/npmtest/node-npmtest-pem)

#### Create private keys and certificates with node.js and io.js

[![NPM](https://nodei.co/npm/pem.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pem)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pem/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pem/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pem/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pem/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pem/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pem/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pem/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pem/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pem/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pem/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pem/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pem/build/test-report.html](https://npmtest.github.io/node-npmtest-pem/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pem/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pem/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pem/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pem/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pem/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pem/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pem/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pem/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "Andris Reinman <andris@kreata.ee>",
    "contributors": [
        {
            "name": "Josef Fröhle",
            "url": "https://www.josef-froehle.de/"
        }
    ],
    "name": "pem",
    "description": "Create private keys and certificates with node.js and io.js",
    "version": "1.9.4",
    "repository": {
        "type": "git",
        "url": "https://github.com/Dexus/pem.git"
    },
    "main": "lib/pem",
    "scripts": {
        "test": "grunt",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post"
    },
    "dependencies": {
        "os-tmpdir": "^1.0.1",
        "which": "^1.2.4"
    },
    "devDependencies": {
        "grunt": "^1.0.1",
        "grunt-contrib-jshint": "^1.1.0",
        "grunt-contrib-nodeunit": "^1.0.0",
        "nodeunit": "^0.10.2",
        "semantic-release": "^6.3.2",
        "semantic-release-tamia": "^1.0.0"
    },
    "optionalDependencies": {},
    "engines": {
        "node": "*",
        "iojs": "*"
    },
    "release": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
