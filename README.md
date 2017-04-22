# npmdoc-nvmw

#### api documentation for  nvmw (v0.2.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-nvmw.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nvmw) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nvmw.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nvmw)

#### Node version manager for Windows

[![NPM](https://nodei.co/npm/nvmw.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nvmw)

- [https://npmdoc.github.io/node-npmdoc-nvmw/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nvmw/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nvmw/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nvmw/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nvmw/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nvmw/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nvmw",
    "description": "Node version manager for Windows",
    "version": "0.2.1",
    "author": "Tom.Huang <hzlhu.dargon@gmail.com>",
    "dependencies": {
        "underscore": "1.4.x",
        "commander": "*",
        "request": "*",
        "colors": "*",
        "adm-zip": "*",
        "rmdir": "*",
        "mkdirp": "*",
        "async": "*",
        "winreg": "*"
    },
    "keys": [
        "Node",
        "version",
        "manager",
        "widnows"
    ],
    "bin": {
        "nvmw": "./bin/nvmw.bat"
    },
    "repository": "git://github.com/nanjingboy/nvmw"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
