# npmtest-grunt-rsync

#### basic test-coverage for  [grunt-rsync (v2.0.1)](https://github.com/jedrichards/grunt-rsync)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-rsync.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-rsync) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-rsync.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-rsync)

#### A Grunt task for accessing the file copying and syncing capabilities of the rsync command line utility. Uses the rsyncwrapper npm module for the core functionality.

[![NPM](https://nodei.co/npm/grunt-rsync.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-rsync)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-rsync/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-rsync/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-rsync/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-rsync/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-rsync/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-rsync/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-rsync/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-rsync/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-rsync/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-rsync/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-rsync/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-rsync/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-rsync/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-rsync/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-rsync/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-rsync/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-rsync/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-rsync/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-rsync/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-rsync/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-rsync/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-rsync",
    "version": "2.0.1",
    "description": "A Grunt task for accessing the file copying and syncing capabilities of the rsync command line utility. Uses the rsyncwrapper npm module for the core functionality.",
    "main": "grunt.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/jedrichards/grunt-rsync.git"
    },
    "homepage": "https://github.com/jedrichards/grunt-rsync",
    "bugs": "https://github.com/jedrichards/grunt-rsync/issues",
    "scripts": {
        "test": "grunt test"
    },
    "dependencies": {
        "rsyncwrapper": "2.0.1"
    },
    "devDependencies": {
        "grunt": "1.0.1",
        "grunt-contrib-clean": "1.0.0",
        "grunt-contrib-jshint": "1.0.0",
        "grunt-shell": "1.3.1",
        "grunt-vows": "0.4.2",
        "vows": "0.8.1"
    },
    "keywords": [
        "rsync",
        "grunt plugin",
        "gruntplugin",
        "grunt",
        "grunt task",
        "syncing",
        "copying",
        "file manipulation",
        "remote",
        "ssh",
        "exclude patterns"
    ],
    "author": {
        "name": "Jed Richards"
    },
    "license": "MIT",
    "engines": {
        "node": ">=0.10.25"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
