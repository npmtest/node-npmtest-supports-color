# npmtest-supports-color

#### basic test coverage for  supports-color (v3.2.3)  [![npm package](https://img.shields.io/npm/v/npmtest-supports-color.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-supports-color) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-supports-color.svg)](https://travis-ci.org/npmtest/node-npmtest-supports-color)

#### Detect whether a terminal supports color

[![NPM](https://nodei.co/npm/supports-color.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/supports-color)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-supports-color/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-supports-color/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-supports-color/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-supports-color/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-supports-color/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-supports-color/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-supports-color/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-supports-color/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-supports-color/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-supports-color/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-supports-color/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-supports-color/build/test-report.html](https://npmtest.github.io/node-npmtest-supports-color/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-supports-color/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-supports-color/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-supports-color/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-supports-color/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-supports-color/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-supports-color/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-supports-color/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-supports-color/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "supports-color",
    "version": "3.2.3",
    "description": "Detect whether a terminal supports color",
    "license": "MIT",
    "repository": "chalk/supports-color",
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "maintainers": [
        "Sindre Sorhus <sindresorhus@gmail.com> (sindresorhus.com)",
        "Joshua Boy Nicolai Appelman <joshua@jbna.nl> (jbna.nl)",
        "JD Ballard <i.am.qix@gmail.com> (github.com/qix-)"
    ],
    "browser": "browser.js",
    "engines": {
        "node": ">=0.8.0"
    },
    "scripts": {
        "test": "xo && mocha",
        "travis": "mocha"
    },
    "files": [
        "index.js",
        "browser.js"
    ],
    "keywords": [
        "color",
        "colour",
        "colors",
        "terminal",
        "console",
        "cli",
        "ansi",
        "styles",
        "tty",
        "rgb",
        "256",
        "shell",
        "xterm",
        "command-line",
        "support",
        "supports",
        "capability",
        "detect",
        "truecolor",
        "16m",
        "million"
    ],
    "dependencies": {
        "has-flag": "^1.0.0"
    },
    "devDependencies": {
        "mocha": "*",
        "require-uncached": "^1.0.2",
        "xo": "*"
    },
    "xo": {
        "envs": [
            "node",
            "mocha"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
