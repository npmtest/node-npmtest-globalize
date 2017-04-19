# npmtest-globalize

#### basic test coverage for  [globalize (v1.2.3)](https://github.com/jquery/globalize)  [![npm package](https://img.shields.io/npm/v/npmtest-globalize.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-globalize) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-globalize.svg)](https://travis-ci.org/npmtest/node-npmtest-globalize)

#### A JavaScript library for internationalization and localization that leverages the official Unicode CLDR JSON data.

[![NPM](https://nodei.co/npm/globalize.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/globalize)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-globalize/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-globalize/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-globalize/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-globalize/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-globalize/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-globalize/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-globalize/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-globalize/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-globalize/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-globalize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-globalize/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-globalize/build/test-report.html](https://npmtest.github.io/node-npmtest-globalize/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-globalize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-globalize/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-globalize/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-globalize/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-globalize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-globalize/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-globalize/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-globalize/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "jQuery Foundation and other contributors",
        "url": "https://github.com/jquery/jquery/blob/master/AUTHORS.txt"
    },
    "bugs": {
        "url": "http://github.com/jquery/globalize/issues"
    },
    "commitplease": {
        "nohook": true
    },
    "dependencies": {
        "cldrjs": "^0.4.6"
    },
    "description": "A JavaScript library for internationalization and localization that leverages the official Unicode CLDR JSON data.",
    "devDependencies": {
        "cldr-data-downloader": "^0.2.5",
        "grunt": "0.4.5",
        "grunt-check-dependencies": "0.6.0",
        "grunt-commitplease": "0.0.5",
        "grunt-compare-size": "0.4.0",
        "grunt-contrib-clean": "0.6.0",
        "grunt-contrib-connect": "0.8.0",
        "grunt-contrib-copy": "0.6.0",
        "grunt-contrib-jshint": "0.11.1",
        "grunt-contrib-qunit": "0.7.0",
        "grunt-contrib-requirejs": "0.4.4",
        "grunt-contrib-uglify": "0.6.0",
        "grunt-contrib-watch": "0.6.1",
        "grunt-git-authors": "^3.1.0",
        "grunt-jscs": "1.8.0",
        "gzip-js": "0.3.2",
        "matchdep": "0.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b6d39ffc43781bcbf6dcf459e15fc9aa30fc4a45",
        "tarball": "https://registry.npmjs.org/globalize/-/globalize-1.2.3.tgz"
    },
    "files": [
        "CONTRIBUTING.md",
        "dist/",
        "!dist/.build",
        "doc/",
        "examples/",
        "!examples/**/bower_components",
        "!examples/**/.tmp-globalize-webpack",
        "!examples/plain-javascript/cldrjs",
        "!examples/plain-javascript/globalize",
        "LICENSE.txt",
        "README.md"
    ],
    "gitHead": "0427587c4b11c6c1cef0213c63662e2f7e0f5016",
    "homepage": "https://github.com/jquery/globalize",
    "keywords": [
        "utility",
        "globalization",
        "internationalization",
        "multilingualization",
        "localization",
        "g11n",
        "i18n",
        "m17n",
        "L10n",
        "localize",
        "format",
        "parse",
        "translate",
        "strings",
        "numbers",
        "dates",
        "times",
        "calendars",
        "plural",
        "plurals",
        "pluralize",
        "cultures",
        "languages",
        "locales",
        "Unicode",
        "CLDR",
        "JSON"
    ],
    "license": "MIT",
    "main": "./dist/node-main.js",
    "maintainers": [
        {
            "name": "jzaefferer"
        },
        {
            "name": "scott.gonzalez"
        },
        {
            "name": "rxaviers"
        }
    ],
    "name": "globalize",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/jquery/globalize.git"
    },
    "scripts": {
        "test": "grunt"
    },
    "version": "1.2.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
