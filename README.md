# npmtest-eslint-plugin-jsx-a11y

#### test coverage for  [eslint-plugin-jsx-a11y (v4.0.0)](https://github.com/evcohen/eslint-plugin-jsx-a11y#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-eslint-plugin-jsx-a11y.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eslint-plugin-jsx-a11y) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eslint-plugin-jsx-a11y.svg)](https://travis-ci.org/npmtest/node-npmtest-eslint-plugin-jsx-a11y)

#### Static AST checker for accessibility rules on JSX elements.

[![NPM](https://nodei.co/npm/eslint-plugin-jsx-a11y.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eslint-plugin-jsx-a11y)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eslint-plugin-jsx-a11y/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-jsx-a11y/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-jsx-a11y/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-jsx-a11y/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-jsx-a11y/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eslint-plugin-jsx-a11y/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eslint-plugin-jsx-a11y/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eslint-plugin-jsx-a11y/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eslint-plugin-jsx-a11y/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-jsx-a11y/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-jsx-a11y/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eslint-plugin-jsx-a11y/build/test-report.html](https://npmtest.github.io/node-npmtest-eslint-plugin-jsx-a11y/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-jsx-a11y/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-jsx-a11y/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eslint-plugin-jsx-a11y/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eslint-plugin-jsx-a11y/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-plugin-jsx-a11y/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-plugin-jsx-a11y/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eslint-plugin-jsx-a11y/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eslint-plugin-jsx-a11y/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ethan Cohen"
    },
    "bugs": {
        "url": "https://github.com/evcohen/eslint-plugin-jsx-a11y/issues"
    },
    "dependencies": {
        "aria-query": "^0.3.0",
        "ast-types-flow": "0.0.7",
        "damerau-levenshtein": "^1.0.0",
        "emoji-regex": "^6.1.0",
        "jsx-ast-utils": "^1.0.0",
        "object-assign": "^4.0.1"
    },
    "description": "Static AST checker for accessibility rules on JSX elements.",
    "devDependencies": {
        "babel-cli": "^6.14.0",
        "babel-core": "^6.14.0",
        "babel-eslint": "^7.0.0",
        "babel-jest": "^18.0.0",
        "babel-plugin-transform-flow-strip-types": "^6.21.0",
        "babel-plugin-transform-object-rest-spread": "^6.20.2",
        "babel-polyfill": "^6.16.0",
        "babel-preset-es2015": "^6.14.0",
        "coveralls": "^2.11.8",
        "eslint": "^3.12.2",
        "eslint-config-airbnb-base": "^11.0.0",
        "eslint-plugin-flowtype": "^2.29.2",
        "eslint-plugin-import": "^2.2.0",
        "expect": "^1.20.2",
        "flow-bin": "^0.38.0",
        "jest": "^18.1.0",
        "jscodeshift": "^0.3.30",
        "minimist": "^1.2.0",
        "rimraf": "^2.5.2",
        "to-ast": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "779bb0fe7b08da564a422624911de10061e048ee",
        "tarball": "https://registry.npmjs.org/eslint-plugin-jsx-a11y/-/eslint-plugin-jsx-a11y-4.0.0.tgz"
    },
    "engines": {
        "node": ">=4.0"
    },
    "gitHead": "24128bb96129b74ad8a11b17924158f1372d3661",
    "homepage": "https://github.com/evcohen/eslint-plugin-jsx-a11y#readme",
    "jest": {
        "coverageReporters": [
            "lcov"
        ],
        "coverageDirectory": "reports",
        "testPathDirs": [
            "<rootDir>/__tests__"
        ],
        "testPathIgnorePatterns": [
            "<rootDir>/__tests__/__util__"
        ]
    },
    "keywords": [
        "eslint",
        "eslintplugin",
        "eslint-plugin",
        "a11y",
        "accessibility",
        "jsx"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "evcohen"
        },
        {
            "name": "jessebeach"
        },
        {
            "name": "lencioni"
        },
        {
            "name": "ljharb"
        }
    ],
    "name": "eslint-plugin-jsx-a11y",
    "optionalDependencies": {},
    "peerDependencies": {
        "eslint": "^2.10.2 || 3.x"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/evcohen/eslint-plugin-jsx-a11y.git"
    },
    "scripts": {
        "build": "rimraf lib && babel src --out-dir lib && cp -R src/util/attributes lib/util/attributes",
        "coveralls": "cat ./reports/lcov.info | coveralls",
        "create": "node ./scripts/create-rule",
        "flow": "flow; test $? -eq 0 -o $? -eq 2",
        "lint": "eslint  --config .eslintrc src __tests__",
        "lint:fix": "npm run lint -- --fix",
        "prepublish": "npm run lint && npm run flow && npm run test && npm run build",
        "pretest": "npm run lint:fix && npm run flow",
        "test": "jest --bail --coverage"
    },
    "version": "4.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
