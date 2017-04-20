# npmtest-unfluff

#### basic test coverage for  [unfluff (v1.1.0)](https://github.com/ageitgey/node-unfluff)  [![npm package](https://img.shields.io/npm/v/npmtest-unfluff.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-unfluff) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-unfluff.svg)](https://travis-ci.org/npmtest/node-npmtest-unfluff)

#### A web page content extractor

[![NPM](https://nodei.co/npm/unfluff.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/unfluff)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-unfluff/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-unfluff/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-unfluff/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-unfluff/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-unfluff/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-unfluff/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-unfluff/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-unfluff/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-unfluff/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-unfluff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-unfluff/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-unfluff/build/test-report.html](https://npmtest.github.io/node-npmtest-unfluff/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-unfluff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-unfluff/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-unfluff/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-unfluff/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-unfluff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-unfluff/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-unfluff/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-unfluff/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Adam Geitgey"
    },
    "bin": {
        "unfluff": "bin/unfluff"
    },
    "bugs": {
        "url": "https://github.com/ageitgey/node-unfluff/issues"
    },
    "dependencies": {
        "cheerio": "~0.17.0",
        "lodash": "~2.4.1",
        "optimist": "~0.6.1",
        "xregexp": "~2.0.0"
    },
    "description": "A web page content extractor",
    "devDependencies": {
        "coffee-script-redux": "2.0.0-beta7",
        "commonjs-everywhere": "0.9.x",
        "deep-equal": "~0.2.1",
        "mocha": "~1.12.1",
        "scopedfs": "~0.1.0",
        "semver": "~2.1.0"
    },
    "directories": {
        "bin": "bin",
        "lib": "lib",
        "test": "test"
    },
    "dist": {
        "shasum": "5f0c1aaf8ef103836c6468113eb716ff59c0b4bb",
        "tarball": "https://registry.npmjs.org/unfluff/-/unfluff-1.1.0.tgz"
    },
    "engines": {
        "node": "0.8.x || 0.9.x || 0.10.x"
    },
    "gitHead": "e757cda5c7f490d0f245d829bd1a58b4fefcb0b1",
    "homepage": "https://github.com/ageitgey/node-unfluff",
    "keywords": [
        "content extraction",
        "html",
        "scraping",
        "scrape",
        "web page",
        "body text"
    ],
    "licenses": [
        {
            "type": "Apache",
            "url": "https://github.com/ageitgey/node-unfluff/blob/master/LICENSE"
        }
    ],
    "main": "lib/unfluff.js",
    "maintainers": [
        {
            "name": "ageitgey"
        }
    ],
    "name": "unfluff",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/ageitgey/node-unfluff.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "1.1.0",
    "warnings": [
        {
            "code": "ENOTSUP",
            "required": {
                "node": "0.8.x || 0.9.x || 0.10.x"
            },
            "pkgid": "unfluff@1.1.0"
        },
        {
            "code": "ENOTSUP",
            "required": {
                "node": "0.8.x || 0.9.x || 0.10.x"
            },
            "pkgid": "unfluff@1.1.0"
        }
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
