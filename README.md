# npmtest-react-ga

#### basic test coverage for  [react-ga (v2.2.0)](https://github.com/react-ga/react-ga)  [![npm package](https://img.shields.io/npm/v/npmtest-react-ga.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-ga) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-ga.svg)](https://travis-ci.org/npmtest/node-npmtest-react-ga)

#### React Google Analytics Module.

[![NPM](https://nodei.co/npm/react-ga.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-ga)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-ga/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-ga/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-ga/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-ga/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-ga/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-ga/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-ga/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-ga/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-ga/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-ga/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-ga/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-ga/build/test-report.html](https://npmtest.github.io/node-npmtest-react-ga/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-ga/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-ga/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-ga/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-ga/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-ga/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-ga/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-ga/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-ga/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-ga",
    "version": "2.2.0",
    "description": "React Google Analytics Module.",
    "main": "src/index.js",
    "scripts": {
        "test": "mocha test/*.test.js && mocha test/**/*.test.js && gulp test",
        "build": "gulp build"
    },
    "repository": {
        "type": "git",
        "url": "git@github.com:react-ga/react-ga"
    },
    "keywords": [
        "React",
        "GA",
        "Google Analytics",
        "Universal Analytics"
    ],
    "author": "@adamlofting",
    "contributors": [
        "@toolness"
    ],
    "license": "Apache-2.0",
    "bugs": {
        "url": "https://github.com/react-ga/react-ga/issues"
    },
    "homepage": "https://github.com/react-ga/react-ga",
    "peerDependencies": {
        "react": ">= 0.14.0"
    },
    "dependencies": {
        "create-react-class": "^15.5.2",
        "object-assign": "^4.0.1",
        "prop-types": "^15.5.6"
    },
    "devDependencies": {
        "browserify": "^13.0.0",
        "browserify-shim": "^3.8.12",
        "del": "^2.2.0",
        "envify": "^4.0.0",
        "gulp": "~3.8.11",
        "gulp-jscs": "^3.0.2",
        "gulp-rename": "~1.2.0",
        "gulp-streamify": "^1.0.2",
        "gulp-uglify": "~1.1.0",
        "jsdom": "^3.0.0",
        "mocha": "^2.2.1",
        "mocha-jsdom": "~1.0.0",
        "react": "^15.0.1",
        "react-addons-test-utils": "^15.0.1",
        "react-dom": "^15.0.1",
        "should": "^5.2.0",
        "sinon": "^1.14.1",
        "vinyl-source-stream": "^1.1.0"
    },
    "browserify-shim": {
        "react": "global:React"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
