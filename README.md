# npmtest-sprite-anim

#### basic test coverage for  sprite-anim (v0.2.0)  [![npm package](https://img.shields.io/npm/v/npmtest-sprite-anim.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sprite-anim) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sprite-anim.svg)](https://travis-ci.org/npmtest/node-npmtest-sprite-anim)

#### Simple spritesheet animation engine

[![NPM](https://nodei.co/npm/sprite-anim.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sprite-anim)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sprite-anim/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sprite-anim/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sprite-anim/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sprite-anim/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sprite-anim/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sprite-anim/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sprite-anim/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sprite-anim/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sprite-anim/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sprite-anim/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sprite-anim/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sprite-anim/build/test-report.html](https://npmtest.github.io/node-npmtest-sprite-anim/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sprite-anim/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sprite-anim/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sprite-anim/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sprite-anim/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sprite-anim/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sprite-anim/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sprite-anim/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sprite-anim/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sprite-anim",
    "version": "0.2.0",
    "description": "Simple spritesheet animation engine",
    "keywords": [
        "spritesheet",
        "sprites",
        "animation",
        "animations",
        "sprite",
        "texture packer"
    ],
    "main": "src/SpriteAnim.js",
    "scripts": {
        "start": "http-server",
        "watch": "watchify src/SpriteAnim.js --s SpriteAnim -o dist/sprite-anim.js -dv",
        "build-dev": "browserify src/SpriteAnim.js --s SpriteAnim -o dist/sprite-anim.js",
        "build-prod": "browserify src/SpriteAnim.js --s SpriteAnim | uglifyjs -o dist/sprite-anim.min.js",
        "build": "npm run build-dev && npm run build-prod",
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "author": "Manuel Odelain",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/manuelodelain/sprite-anim.git"
    },
    "dependencies": {
        "inherits": "^2.0.1",
        "raf": "^3.0.0",
        "tiny-emitter": "^1.0.0"
    },
    "devDependencies": {
        "browserify": "^10.2.3",
        "http-server": "^0.8.0",
        "uglifyjs": "^2.4.10",
        "watchify": "^3.2.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
