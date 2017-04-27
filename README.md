# npmtest-ticons

#### basic test coverage for  [ticons (v0.23.1)](https://github.com/fokkezb/ticons-cli)  [![npm package](https://img.shields.io/npm/v/npmtest-ticons.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ticons) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ticons.svg)](https://travis-ci.org/npmtest/node-npmtest-ticons)

#### Generate Titanium & Alloy icons, splash and other assets

[![NPM](https://nodei.co/npm/ticons.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ticons)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ticons/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ticons/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ticons/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ticons/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ticons/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ticons/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ticons/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ticons/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ticons/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ticons/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ticons/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ticons/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ticons/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ticons/build/test-report.html](https://npmtest.github.io/node-npmtest-ticons/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ticons/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ticons/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ticons/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ticons/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ticons/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ticons/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ticons/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ticons/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Fokke Zandbergen",
        "url": "http://fokkezb.nl"
    },
    "bin": {
        "ticons": "./cli.js"
    },
    "bugs": {
        "url": "https://github.com/fokkezb/ticons-cli/issues"
    },
    "dependencies": {
        "async": "^0.2.10",
        "colors": "^0.6.2",
        "commander": "^2.1.0",
        "fs-extended": "^0.2.0",
        "gm": "~1.17.0",
        "semver": "^5.0.1",
        "underscore": "^1.5.2",
        "update-notifier": "^0.1.10"
    },
    "description": "Generate Titanium & Alloy icons, splash and other assets",
    "devDependencies": {
        "grunt": "~0.4.2",
        "grunt-mocha-test": "~0.8.1",
        "image-size": "^0.3.5",
        "mocha": "~1.17.0",
        "should": "~3.1.2"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "6eed4a139e2be7a6b3880329d890f1d1942f739e",
        "tarball": "https://registry.npmjs.org/ticons/-/ticons-0.23.1.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "b7b3e6c30a76e845d97cbd4946297a571c0f4fec",
    "homepage": "https://github.com/fokkezb/ticons-cli",
    "keywords": [
        "titanium",
        "alloy",
        "appcelerator",
        "icons",
        "splashes",
        "launch",
        "images",
        "assets",
        "generator"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "fokkezb"
        }
    ],
    "name": "ticons",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/fokkezb/ticons-cli.git"
    },
    "scripts": {
        "major": "grunt test && npm version major -m 'bump version' && npm publish && git push && git push --tags",
        "minor": "grunt test && npm version minor -m 'bump version' && npm publish && git push && git push --tags",
        "patch": "grunt test && npm version patch -m 'bump version' && npm publish && git push && git push --tags",
        "test": "grunt test"
    },
    "version": "0.23.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
