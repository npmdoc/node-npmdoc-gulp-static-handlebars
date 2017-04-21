# npmdoc-gulp-static-handlebars

#### api documentation for  gulp-static-handlebars (v1.2.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-static-handlebars.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-static-handlebars) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-static-handlebars.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-static-handlebars)

#### Compile handlebars into static files, taking data, partials and helpers from outside sources like files, database, and json through callbacks and promises.

[![NPM](https://nodei.co/npm/gulp-static-handlebars.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-static-handlebars)

- [https://npmdoc.github.io/node-npmdoc-gulp-static-handlebars/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-static-handlebars/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-static-handlebars/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-static-handlebars/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-static-handlebars/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-static-handlebars/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-static-handlebars",
    "version": "1.2.0",
    "description": "Compile handlebars into static files, taking data, partials and helpers from outside sources like files, database, and json through callbacks and promises.",
    "main": "index.js",
    "repository": "http://github.com/TakenPilot/gulp-static-handlebars.git",
    "scripts": {
        "test": "./node_modules/.bin/mocha -R mocha-lcov-reporter | ./node_modules/coveralls/bin/coveralls.js"
    },
    "config": {
        "blanket": {
            "pattern": "index.js",
            "data-cover-never": "node_modules"
        }
    },
    "keywords": [
        "gulpfriendly",
        "gulpplugin",
        "handlebars",
        "static",
        "pipe",
        "promise",
        "async"
    ],
    "author": "Dane Stuckel",
    "license": "ISC",
    "dependencies": {
        "bluebird": "^2.9",
        "gulp-util": "^3.0",
        "handlebars": "^4.0",
        "lodash": "^3.0",
        "readable-stream": "^2.0",
        "through2": "^2.0"
    },
    "devDependencies": {
        "blanket": "^1.1",
        "chai": "^3.4",
        "coveralls": "^2.11",
        "es6-promise": "^3.0",
        "gulp": "^3.8",
        "gulp-rename": "^1.2.0",
        "mocha": "^2.1",
        "mocha-lcov-reporter": "^1.0",
        "sinon": "^1.12",
        "vinyl": "^1.0",
        "vinyl-fs": "^2.2"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
