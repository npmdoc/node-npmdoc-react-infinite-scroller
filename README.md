# npmdoc-react-infinite-scroller

#### api documentation for  react-infinite-scroller (v1.0.8)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-infinite-scroller.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-infinite-scroller) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-infinite-scroller.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-infinite-scroller)

#### Infinite scroll component for React in ES6

[![NPM](https://nodei.co/npm/react-infinite-scroller.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-infinite-scroller)

- [https://npmdoc.github.io/node-npmdoc-react-infinite-scroller/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-infinite-scroller/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-infinite-scroller/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-infinite-scroller/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-infinite-scroller/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-infinite-scroller/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-infinite-scroller",
    "version": "1.0.8",
    "description": "Infinite scroll component for React in ES6",
    "main": "dist/InfiniteScroll.js",
    "jsnext:main": "src/InfiniteScroll.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/CassetteRocks/react-infinite-scroller.git"
    },
    "scripts": {
        "build": "mkdir -p dist && babel src/InfiniteScroll.js --presets es2015,react,stage-2 --plugins add-module-exports --out-file dist/InfiniteScroll.js",
        "prepublish": "npm run build"
    },
    "keywords": [
        "infinite",
        "scroll",
        "react"
    ],
    "author": "CassetteRocks",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/CassetteRocks/react-infinite-scroller/issues"
    },
    "devDependencies": {
        "babel-cli": "^6.6.5",
        "babel-plugin-add-module-exports": "^0.1.2",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-2": "^6.13.0",
        "prop-types": "^15.5.8",
        "react": "^0.14.0 || ^15.0.1"
    },
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
