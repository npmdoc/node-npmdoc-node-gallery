# npmdoc-node-gallery

#### api documentation for  [node-gallery (v1.1.0)](http://www.github.com/cianclarke/node-gallery)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-gallery.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-gallery) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-gallery.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-gallery)

#### NodeJS Photo Gallery using directory structure & exif info to output a gallery

[![NPM](https://nodei.co/npm/node-gallery.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-gallery)

- [https://npmdoc.github.io/node-npmdoc-node-gallery/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-gallery/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-gallery/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-gallery/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-gallery/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-gallery/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Cian Clarke",
        "url": "http://www.cianclarke.com"
    },
    "dependencies": {
        "ejs": "2.0.8",
        "exif": "git://github.com/cianclarke/node-exif.git",
        "express": "4.10.7",
        "gm": "^1.17.0",
        "imagemagick-stream": "^1.1.0",
        "memory-cache": "^0.1.1",
        "underscore": "^1.7.0"
    },
    "description": "NodeJS Photo Gallery using directory structure & exif info to output a gallery",
    "devDependencies": {
        "colors": "1.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "402d4680c817fd7f0c58512b51f190ae30c16457",
        "tarball": "https://registry.npmjs.org/node-gallery/-/node-gallery-1.1.0.tgz"
    },
    "engines": {
        "node": ">=0.6.2"
    },
    "gitHead": "67961ff9cd22dceaac3dda2d65575360d96e076d",
    "homepage": "http://www.github.com/cianclarke/node-gallery",
    "license": "MIT",
    "main": "lib/gallery.js",
    "maintainers": [
        {
            "name": "cianclarke"
        }
    ],
    "name": "node-gallery",
    "optionalDependencies": {},
    "repository": {
        "url": ""
    },
    "scripts": {
        "test": "node test/test-gallery.js ; node test/test-album.js ; node test/test-photo.js"
    },
    "subdomain": "node-gallery",
    "version": "1.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
