# npmtest-np

#### basic test coverage for  np (v2.13.2)  [![npm package](https://img.shields.io/npm/v/npmtest-np.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-np) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-np.svg)](https://travis-ci.org/npmtest/node-npmtest-np)

#### A better `npm publish`

[![NPM](https://nodei.co/npm/np.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/np)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-np/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-np/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-np/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-np/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-np/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-np/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-np/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-np/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-np/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-np/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-np/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-np/build/test-report.html](https://npmtest.github.io/node-npmtest-np/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-np/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-np/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-np/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-np/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-np/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-np/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-np/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-np/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "np",
    "version": "2.13.2",
    "description": "A better 'npm publish'",
    "license": "MIT",
    "repository": "sindresorhus/np",
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "maintainers": [
        {
            "name": "Sam Verschueren",
            "url": "github.com/SamVerschueren"
        }
    ],
    "bin": "cli.js",
    "engines": {
        "node": ">=4"
    },
    "scripts": {
        "test": "xo && ava"
    },
    "files": [
        "index.js",
        "cli.js",
        "lib"
    ],
    "keywords": [
        "cli-app",
        "cli",
        "npm",
        "publish",
        "git",
        "push",
        "version",
        "bump",
        "commit"
    ],
    "dependencies": {
        "any-observable": "^0.2.0",
        "chalk": "^1.1.3",
        "del": "^2.2.0",
        "execa": "^0.6.3",
        "has-yarn": "^1.0.0",
        "inquirer": "^3.0.6",
        "listr": "^0.11.0",
        "log-symbols": "^1.0.2",
        "meow": "^3.7.0",
        "read-pkg-up": "^2.0.0",
        "rxjs": "^5.0.0-beta.9",
        "semver": "^5.1.0",
        "split": "^1.0.0",
        "stream-to-observable": "^0.2.0",
        "update-notifier": "^2.1.0"
    },
    "devDependencies": {
        "ava": "*",
        "xo": "*"
    },
    "xo": {
        "esnext": true
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
