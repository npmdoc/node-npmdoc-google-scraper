# npmdoc-google-scraper

#### api documentation for  [google-scraper (v1.1.2)](https://github.com/jsnomad/Google-Scraper#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-google-scraper.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-google-scraper) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-google-scraper.svg)](https://travis-ci.org/npmdoc/node-npmdoc-google-scraper)

#### Extract links from Google SERP

[![NPM](https://nodei.co/npm/google-scraper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/google-scraper)

- [https://npmdoc.github.io/node-npmdoc-google-scraper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-google-scraper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-google-scraper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-google-scraper/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-google-scraper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-google-scraper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Thomas Blanc-hector"
    },
    "bugs": {
        "url": "https://github.com/jsnomad/Google-Scraper/issues"
    },
    "dependencies": {
        "cheerio": "^0.22.0",
        "request": "^2.79.0"
    },
    "description": "Extract links from Google SERP",
    "devDependencies": {
        "babel-cli": "^6.5.1",
        "babel-eslint": "^7.1.1",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-polyfill": "^6.5.0",
        "babel-preset-es2015": "^6.3.13",
        "babel-register": "^6.3.13",
        "chai": "^3.5.0",
        "eslint": "^3.12.2",
        "eslint-config-airbnb": "^13.0.0",
        "eslint-plugin-import": "^2.2.0",
        "mocha": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "28e0f0d9b6a3508e235a122157df57c6f7c60439",
        "tarball": "https://registry.npmjs.org/google-scraper/-/google-scraper-1.1.2.tgz"
    },
    "gitHead": "79195dee4b54a7aa1684955dcceb829dabb93f73",
    "homepage": "https://github.com/jsnomad/Google-Scraper#readme",
    "keywords": [
        "google",
        "scrape",
        "scraping",
        "scraper"
    ],
    "license": "MIT",
    "main": "./index",
    "maintainers": [
        {
            "name": "jsnomad"
        }
    ],
    "name": "google-scraper",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jsnomad/Google-Scraper.git"
    },
    "scripts": {
        "compile": "babel -d lib/ src/",
        "lint": "eslint ./src",
        "mocha": "mocha --timeout 15000 --compilers js:babel-register --require babel-polyfill",
        "prepublish": "npm run compile",
        "test": "npm run compile && npm run lint && npm run mocha"
    },
    "version": "1.1.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
