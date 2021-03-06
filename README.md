# npmtest-postcss-cssnext

#### basic test coverage for  [postcss-cssnext (v2.10.0)](http://cssnext.io/)  [![npm package](https://img.shields.io/npm/v/npmtest-postcss-cssnext.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-postcss-cssnext) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-postcss-cssnext.svg)](https://travis-ci.org/npmtest/node-npmtest-postcss-cssnext)

#### Use tomorrow’s CSS syntax, today

[![NPM](https://nodei.co/npm/postcss-cssnext.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/postcss-cssnext)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-postcss-cssnext/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-cssnext/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-cssnext/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-postcss-cssnext/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-cssnext/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-postcss-cssnext/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-postcss-cssnext/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-postcss-cssnext/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-postcss-cssnext/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-cssnext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-postcss-cssnext/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-postcss-cssnext/build/test-report.html](https://npmtest.github.io/node-npmtest-postcss-cssnext/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-postcss-cssnext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-postcss-cssnext/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-postcss-cssnext/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-postcss-cssnext/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-postcss-cssnext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-postcss-cssnext/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-postcss-cssnext/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-postcss-cssnext/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Maxime Thirouin"
    },
    "babel": {
        "presets": [
            "babel-preset-react",
            "babel-preset-es2015",
            "babel-preset-stage-1"
        ]
    },
    "bugs": {
        "url": "https://github.com/MoOx/postcss-cssnext/issues"
    },
    "dependencies": {
        "autoprefixer": "^6.0.2",
        "caniuse-api": "^1.5.3",
        "chalk": "^1.1.1",
        "pixrem": "^3.0.0",
        "pleeease-filters": "^3.0.0",
        "postcss": "^5.0.4",
        "postcss-apply": "^0.3.0",
        "postcss-attribute-case-insensitive": "^1.0.1",
        "postcss-calc": "^5.0.0",
        "postcss-color-function": "^2.0.0",
        "postcss-color-gray": "^3.0.0",
        "postcss-color-hex-alpha": "^2.0.0",
        "postcss-color-hsl": "^1.0.5",
        "postcss-color-hwb": "^2.0.0",
        "postcss-color-rebeccapurple": "^2.0.0",
        "postcss-color-rgb": "^1.1.4",
        "postcss-color-rgba-fallback": "^2.0.0",
        "postcss-custom-media": "^5.0.0",
        "postcss-custom-properties": "^5.0.0",
        "postcss-custom-selectors": "^3.0.0",
        "postcss-font-family-system-ui": "^1.0.1",
        "postcss-font-variant": "^2.0.0",
        "postcss-initial": "^1.3.1",
        "postcss-media-minmax": "^2.1.0",
        "postcss-nesting": "^2.0.5",
        "postcss-pseudo-class-any-link": "^1.0.0",
        "postcss-pseudoelements": "^3.0.0",
        "postcss-replace-overflow-wrap": "^1.0.0",
        "postcss-selector-matches": "^2.0.0",
        "postcss-selector-not": "^2.0.0"
    },
    "description": "Use tomorrow’s CSS syntax, today",
    "devDependencies": {
        "babel-cli": "^6.6.5",
        "babel-core": "^6.7.2",
        "babel-loader": "^6.2.4",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-1": "^6.5.0",
        "babel-tape-runner": "^2.0.1",
        "classnames": "^2.1.1",
        "css-loader": "^0.13.1",
        "cssrecipes-custom-media-queries": "^0.3.0",
        "cssrecipes-defaults": "^0.5.0",
        "cssrecipes-grid": "^0.4.0",
        "cssrecipes-utils": "^0.5.0",
        "cssrecipes-vertical-rhythm": "^0.6.0",
        "eslint": "^2.4.0",
        "eslint-config-i-am-meticulous": "^3.0.0",
        "eslint-loader": "^1.0.0",
        "eslint-plugin-react": "^3.0.0",
        "extract-text-webpack-plugin": "^0.8.0",
        "file-loader": "^0.8.3",
        "highlight.js": "^8.6.0",
        "isogram": "^0.5.0",
        "js-yaml": "^3.3.1",
        "json-loader": "^0.5.2",
        "markdown-it": "^4.2.1",
        "markdown-it-toc-and-anchor": "^1.0.1",
        "metalsmith": "^2.0.1",
        "metalsmith-collections": "^0.7.0",
        "metalsmith-filenames": "^1.0.0",
        "metalsmith-md": "^2.0.1",
        "metalsmith-react": "^2.0.1",
        "metalsmith-rename": "^1.0.0",
        "metalsmith-rss": "^1.0.0",
        "metalsmith-url": "^1.0.0",
        "metalsmith-watch": "^1.0.1",
        "nano-logger": "^1.0.0",
        "node-libs-browser": "^0.5.0",
        "normalize.css": "^3.0.3",
        "npmpub": "^3.1.0",
        "object-assign": "^3.0.0",
        "opn": "^1.0.2",
        "postcss-browser-reporter": "^0.4.0",
        "postcss-import": "^7.1.3",
        "postcss-loader": "^0.8.0",
        "postcss-reporter": "^1.3.0",
        "postcss-url": "^5.0.2",
        "react": "^15.0.0-rc.1",
        "react-dom": "^15.0.0-rc.1",
        "react-svg-inline": "^1.0.1",
        "rimraf": "^2.4.3",
        "style-loader": "^0.12.2",
        "tape": "^4.2.0",
        "to-slug-case": "^0.1.2",
        "webpack": "^1.9.7",
        "webpack-dev-server": "^1.8.2",
        "webpack-nano-logs": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "30e0dddcfb978eae2523a340aa2c8ba49c5d7103",
        "tarball": "https://registry.npmjs.org/postcss-cssnext/-/postcss-cssnext-2.10.0.tgz"
    },
    "eslintConfig": {
        "extends": "eslint-config-i-am-meticulous/react"
    },
    "files": [
        "docs/content",
        "lib",
        "src",
        "!**/__tests__"
    ],
    "gitHead": "6577f6c196325e5e10d4b4ce704d5987b268433a",
    "homepage": "http://cssnext.io/",
    "keywords": [
        "postcss",
        "postcss-plugin",
        "css",
        "w3c",
        "cssnext"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "moox"
        }
    ],
    "name": "postcss-cssnext",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/MoOx/postcss-cssnext.git"
    },
    "scripts": {
        "#lint": "even if there is a .eslintignore symlink, we use an explicit command because windows don't like unix symlink",
        "#tape": "to avoid really slow tests, we run babel once & run tests on the result",
        "_docs-deploy": "GIT_DEPLOY_DIR=docs/dist ./docs/scripts/deploy-to-gh-pages.sh -v",
        "babelify": "babel src --out-dir lib",
        "docs-build": "babel-node docs/scripts/build",
        "docs-deploy": "npm run docs-test && npm run _docs-deploy",
        "docs-start": "npm run docs-build -- --dev --dev-server --open",
        "docs-test": "npm run docs-build -- --production",
        "lint": "eslint --ignore-path .gitignore .",
        "postrelease": "npm run docs-deploy",
        "prebabelify": "rimraf lib",
        "predocs-start": "npm run prepublish",
        "prepublish": "npm run babelify",
        "release": "npmpub",
        "tape": "tape \"lib/__tests__/*.js\"",
        "test": "npm run lint && npm run babelify && npm run tape"
    },
    "version": "2.10.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
