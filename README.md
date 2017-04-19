# npmtest-react-validation

#### test coverage for  [react-validation (v2.10.9)](https://github.com/Lesha-spr/react-validation)  [![npm package](https://img.shields.io/npm/v/npmtest-react-validation.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-validation) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-validation.svg)](https://travis-ci.org/npmtest/node-npmtest-react-validation)

#### validation components

[![NPM](https://nodei.co/npm/react-validation.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-validation)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-validation/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-validation/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-validation/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-validation/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-validation/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-validation/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-validation/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-validation/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-validation/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-validation/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-validation/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-validation/build/test-report.html](https://npmtest.github.io/node-npmtest-react-validation/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-validation/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-validation/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-validation/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-validation/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-validation/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-validation/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-validation/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-validation/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Oleksii An"
    },
    "bugs": {
        "url": "https://github.com/Lesha-spr/react-validation/issues"
    },
    "dependencies": {},
    "description": "validation components",
    "devDependencies": {
        "babel-core": "^6.17.0",
        "babel-eslint": "^7.0.0",
        "babel-jest": "^16.0.0",
        "babel-loader": "^6.2.5",
        "babel-plugin-transform-decorators": "^6.13.0",
        "babel-plugin-transform-es2015-computed-properties": "^6.8.0",
        "babel-plugin-transform-object-assign": "^6.8.0",
        "babel-plugin-transform-runtime": "^6.15.0",
        "babel-preset-es2015": "^6.16.0",
        "babel-preset-react": "^6.16.0",
        "babel-preset-stage-0": "^6.16.0",
        "browser-sync": "^2.17.1",
        "connect-history-api-fallback": "^1.3.0",
        "coveralls": "^2.11.14",
        "enzyme": "^2.5.0",
        "eslint": "^3.7.1",
        "eslint-config-airbnb": "^12.0.0",
        "eslint-loader": "^1.5.0",
        "eslint-plugin-import": "^1.16.0",
        "eslint-plugin-jsx-a11y": "^2.2.3",
        "eslint-plugin-react": "^6.3.0",
        "extract-text-webpack-plugin": "^1.0.1",
        "jest-cli": "^16.0.1",
        "react": "^15.3.2",
        "react-addons-test-utils": "^15.3.2",
        "react-dom": "^15.3.2",
        "react-hot-loader": "^1.3.0",
        "validator": "^6.1.0",
        "webpack": "^1.13.2",
        "webpack-dev-middleware": "^1.8.4",
        "webpack-hot-middleware": "^2.12.2"
    },
    "directories": {},
    "dist": {
        "shasum": "f56e32cabcf22d53d82af34a7bed80f2b22ba7c4",
        "tarball": "https://registry.npmjs.org/react-validation/-/react-validation-2.10.9.tgz"
    },
    "gitHead": "39365e2c55906876fe60a75814356e475e5636a5",
    "homepage": "https://github.com/Lesha-spr/react-validation",
    "jest": {
        "collectCoverage": true,
        "coverageThreshold": {
            "global": {
                "branches": 90,
                "functions": 90,
                "lines": 90,
                "statements": 90
            }
        },
        "testPathDirs": [
            "<rootDir>/lib/src/"
        ],
        "moduleNameMapper": {
            "^.+\\.(jpg|jpeg|png|gif|eot|otf|webp|svg|ttf|woff|woff2|mp4|webm|wav|mp3|m4a|aac|oga)$": "<rootDir>/__mocks__/fileMock.js",
            "^.+\\.(css|scss|less)$": "<rootDir>/__mocks__/styleMock.js"
        }
    },
    "keywords": [
        "react",
        "validation",
        "react component",
        "react validation"
    ],
    "license": "ISC",
    "main": "lib/build/validation.js",
    "maintainers": [
        {
            "name": "lesha-spr"
        }
    ],
    "name": "react-validation",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "*",
        "classnames": "*"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Lesha-spr/react-validation.git"
    },
    "scripts": {
        "build": "webpack --config ./webpack/webpack.config.build && webpack --config ./webpack/webpack.config.minify",
        "dev": "node dev-server",
        "gh-pages": "webpack --config ./webpack/webpack.config.gh-pages",
        "test": "node --harmony_proxies node_modules/.bin/jest --coverage && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js",
        "test:dev": "jest"
    },
    "version": "2.10.9"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
