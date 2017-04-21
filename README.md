# npmtest-gulp-jsdoc3

#### basic test coverage for  [gulp-jsdoc3 (v1.0.1)](https://github.com/mlucool/gulp-jsdoc3#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-jsdoc3.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-jsdoc3) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-jsdoc3.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-jsdoc3)

#### gulp integration for jsdoc3 cli

[![NPM](https://nodei.co/npm/gulp-jsdoc3.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-jsdoc3)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-jsdoc3/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-jsdoc3/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-jsdoc3/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-jsdoc3/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-jsdoc3/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-jsdoc3/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-jsdoc3/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-jsdoc3/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-jsdoc3/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-jsdoc3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-jsdoc3/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-jsdoc3/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-jsdoc3/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-jsdoc3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-jsdoc3/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-jsdoc3/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-jsdoc3/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-jsdoc3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-jsdoc3/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-jsdoc3/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-jsdoc3/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-jsdoc3",
    "version": "1.0.1",
    "description": "gulp integration for jsdoc3 cli",
    "main": "index.js",
    "files": [
        "dist",
        "docs",
        "index.js",
        "src"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mlucool/gulp-jsdoc3.git"
    },
    "bugs": {
        "url": "https://github.com/mlucool/gulp-jsdoc3/issues"
    },
    "homepage": "https://github.com/mlucool/gulp-jsdoc3#readme",
    "scripts": {
        "lint": "gulp lint",
        "test": "gulp test",
        "preversion": "echo \"Another version! Keep up the good work!\"",
        "version": "",
        "postversion": "git push && git push --tags",
        "prepublish": "gulp default",
        "coveralls": "gulp test && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js"
    },
    "keywords": [
        "gulp",
        "jsdoc",
        "jsdoc3",
        "javascript",
        "gulpplugin",
        "documentation"
    ],
    "author": {
        "name": "Marc Udoff"
    },
    "pre-commit": [
        "lint",
        "test"
    ],
    "license": "Apache-2.0",
    "dependencies": {
        "bluebird": "^3.1.1",
        "debug": "^2.2.0",
        "gulp-util": "^3.0.7",
        "ink-docstrap": "^1.1.4",
        "jsdoc": "^3.4.1",
        "map-stream": "0.0.6",
        "tmp": "0.0.28"
    },
    "devDependencies": {
        "babel-cli": "^6.3.15",
        "babel-core": "^6.3.15",
        "babel-eslint": "^4.1.6",
        "babel-plugin-transform-object-assign": "^6.8.0",
        "babel-preset-es2015": "^6.3.13",
        "chai": "^3.4.1",
        "coveralls": "^2.11.6",
        "eslint": "^1.10.3",
        "eslint-plugin-babel": "^3.0.0",
        "gulp": "^3.9.0",
        "gulp-babel": "^6.1.1",
        "gulp-eslint": "^1.1.1",
        "gulp-istanbul": "^0.10.3",
        "gulp-mocha": "^2.2.0",
        "gulp-sourcemaps": "^1.6.0",
        "isparta": "^4.0.0",
        "mocha": "^2.3.4",
        "mock-spawn": "^0.2.6",
        "pre-commit": "^1.1.2",
        "run-sequence": "^1.1.5"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
