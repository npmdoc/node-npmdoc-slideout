# npmdoc-slideout

#### api documentation for  slideout (v1.0.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-slideout.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-slideout) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-slideout.svg)](https://travis-ci.org/npmdoc/node-npmdoc-slideout)

#### A touch slideout navigation menu for your mobile web apps.

[![NPM](https://nodei.co/npm/slideout.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/slideout)

- [https://npmdoc.github.io/node-npmdoc-slideout/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-slideout/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-slideout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-slideout/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-slideout/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-slideout/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "slideout",
    "repository": "git@github.com:mango/slideout.git",
    "description": "A touch slideout navigation menu for your mobile web apps.",
    "author": "Guille Paz <guille87paz@gmail.com>",
    "version": "1.0.1",
    "scripts": {
        "build": "node browserify.js",
        "test": "npm run build && istanbul cover _mocha",
        "dist": "node browserify.js && uglifyjs ./dist/slideout.js -m -o ./dist/slideout.min.js",
        "hint": "jshint index.js"
    },
    "dependencies": {
        "decouple": "0.0.2",
        "emitter": "git+https://github.com/Mango/emitter.git#0.0.7"
    },
    "devDependencies": {
        "better-assert": "1.0.2",
        "browserify": "13.1.1",
        "coveralls": "2.11.15",
        "istanbul": "0.4.5",
        "jsdom": "9.8.3",
        "jshint": "2.9.4",
        "mocha": "3.1.2",
        "uglify-js": "2.7.4"
    },
    "main": "index.js",
    "keywords": [
        "slideout",
        "offcanvas",
        "menu",
        "touch"
    ],
    "license": "MIT",
    "spm": {
        "dependencies": {
            "decouple": "0.0.2",
            "emitter": "git+https://github.com/Mango/emitter.git#0.0.7"
        },
        "main": "index.js"
    },
    "filename": "slideout.min.js",
    "autoupdate": {
        "source": "git",
        "target": "git://github.com/Mango/slideout.git",
        "basePath": "dist",
        "files": [
            "*.js"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
