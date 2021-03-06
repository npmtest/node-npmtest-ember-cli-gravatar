# npmtest-ember-cli-gravatar

#### basic test coverage for  [ember-cli-gravatar (v3.8.3)](https://github.com/johnotander/ember-cli-gravatar#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-cli-gravatar.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-cli-gravatar) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-cli-gravatar.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-cli-gravatar)

#### Component for gravatar image tags

[![NPM](https://nodei.co/npm/ember-cli-gravatar.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-cli-gravatar)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-cli-gravatar/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-gravatar/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-gravatar/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-cli-gravatar/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-gravatar/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ember-cli-gravatar/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ember-cli-gravatar/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-cli-gravatar/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-cli-gravatar/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-cli-gravatar/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-cli-gravatar/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-gravatar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-gravatar/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-cli-gravatar/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-cli-gravatar/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-cli-gravatar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-gravatar/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-cli-gravatar/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-cli-gravatar/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-cli-gravatar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-cli-gravatar/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-cli-gravatar/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-cli-gravatar/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "John Otander"
    },
    "bugs": {
        "url": "https://github.com/johnotander/ember-cli-gravatar/issues"
    },
    "dependencies": {
        "blueimp-md5": "^2.7.0",
        "broccoli-funnel": "^1.2.0",
        "broccoli-merge-trees": "^2.0.0",
        "ember-cli-babel": "^5.1.6",
        "ember-cli-htmlbars": "^1.0.3"
    },
    "description": "Component for gravatar image tags",
    "devDependencies": {
        "broccoli-asset-rev": "^2.4.2",
        "ember-ajax": "0.7.1",
        "ember-cli": "2.4.3",
        "ember-cli-app-version": "^1.0.0",
        "ember-cli-dependency-checker": "^1.2.0",
        "ember-cli-htmlbars": "^1.0.3",
        "ember-cli-htmlbars-inline-precompile": "^0.3.1",
        "ember-cli-inject-live-reload": "^1.4.0",
        "ember-cli-qunit": "^1.4.0",
        "ember-cli-release": "0.2.8",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-data": "^2.4.2",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.5.1",
        "ember-resolver": "^2.0.3",
        "ember-try": "^0.2.2",
        "loader.js": "^4.0.1"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "0d91c58d0095cf0fa522072c710936fe863cebe6",
        "tarball": "https://registry.npmjs.org/ember-cli-gravatar/-/ember-cli-gravatar-3.8.3.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "932070e48a4cc9f00b2fec4784dc317d0c6b7535",
    "homepage": "https://github.com/johnotander/ember-cli-gravatar#readme",
    "keywords": [
        "gravatar",
        "avatar",
        "component",
        "ember-addon"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "johno"
        }
    ],
    "name": "ember-cli-gravatar",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/johnotander/ember-cli-gravatar.git"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember try:testall"
    },
    "version": "3.8.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
