# npmtest-opn-cli

#### basic test coverage for  [opn-cli (v3.1.0)](https://github.com/sindresorhus/opn-cli#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-opn-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-opn-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-opn-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-opn-cli)

#### A better node-open. Opens stuff like websites, files, executables. Cross-platform.

[![NPM](https://nodei.co/npm/opn-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/opn-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-opn-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-opn-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-opn-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-opn-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-opn-cli/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-opn-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-opn-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-opn-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-opn-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-opn-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-opn-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-opn-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-opn-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-opn-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-opn-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-opn-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-opn-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-opn-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-opn-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-opn-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-opn-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "bin": {
        "opn": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/sindresorhus/opn-cli/issues"
    },
    "dependencies": {
        "file-type": "^3.6.0",
        "get-stdin": "^5.0.1",
        "meow": "^3.7.0",
        "opn": "^4.0.0",
        "temp-write": "^2.1.0"
    },
    "description": "A better node-open. Opens stuff like websites, files, executables. Cross-platform.",
    "devDependencies": {
        "ava": "*",
        "execa": "^0.2.2",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "f819ae6cae0b411bd0149b8560fe6c88adad20f8",
        "tarball": "https://registry.npmjs.org/opn-cli/-/opn-cli-3.1.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "cli.js"
    ],
    "gitHead": "04bdc5a2d4cd85561d94ed2cbcf3d02a497ebfbe",
    "homepage": "https://github.com/sindresorhus/opn-cli#readme",
    "keywords": [
        "cli-app",
        "cli",
        "app",
        "open",
        "opn",
        "opener",
        "opens",
        "launch",
        "start",
        "xdg-open",
        "xdg",
        "default",
        "cmd",
        "browser",
        "editor",
        "executable",
        "exe",
        "url",
        "urls",
        "arguments",
        "args",
        "spawn",
        "exec",
        "child",
        "process",
        "website",
        "file"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "sindresorhus"
        }
    ],
    "name": "opn-cli",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/opn-cli.git"
    },
    "scripts": {
        "test": "xo && ava"
    },
    "version": "3.1.0",
    "xo": {
        "esnext": true
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
