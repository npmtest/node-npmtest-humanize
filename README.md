# npmtest-humanize

#### basic test-coverage for  [humanize (v0.0.9)](https://github.com/taijinlee/humanize)  [![npm package](https://img.shields.io/npm/v/npmtest-humanize.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-humanize) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-humanize.svg)](https://travis-ci.org/npmtest/node-npmtest-humanize)

#### Javascript string formatter for human readability

[![NPM](https://nodei.co/npm/humanize.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/humanize)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-humanize/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-humanize/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-humanize/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-humanize/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-humanize/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-humanize/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-humanize/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-humanize/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-humanize/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-humanize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-humanize/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-humanize/build/test-report.html](https://npmtest.github.io/node-npmtest-humanize/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-humanize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-humanize/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-humanize/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-humanize/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-humanize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-humanize/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-humanize/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-humanize/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tai-Jin Lee"
    },
    "bugs": {
        "url": "https://github.com/taijinlee/humanize/issues"
    },
    "dependencies": {},
    "description": "Javascript string formatter for human readability",
    "devDependencies": {
        "jshint": "0.7.1",
        "mocha": "1.0.3",
        "should": "0.6.3"
    },
    "directories": {},
    "dist": {
        "shasum": "1994ffaecdfe9c441ed2bdac7452b7bb4c9e41a4",
        "tarball": "https://registry.npmjs.org/humanize/-/humanize-0.0.9.tgz"
    },
    "engines": {
        "node": "*"
    },
    "homepage": "https://github.com/taijinlee/humanize",
    "keywords": [
        "util",
        "client",
        "browser"
    ],
    "main": "humanize.js",
    "maintainers": [
        {
            "name": "taijin"
        }
    ],
    "name": "humanize",
    "optionalDependencies": {},
    "readmeFilename": "README.md",
    "repository": {
        "type": "git",
        "url": "git://github.com/taijinlee/humanize.git"
    },
    "scripts": {
        "test": "./node_modules/jshint/bin/hint humanize.js; find specs -type f -a -name *.spec.js -exec ./node_modules/mocha/bin/mocha --globals requirejsVars -R list --require should {} \\;"
    },
    "version": "0.0.9",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
