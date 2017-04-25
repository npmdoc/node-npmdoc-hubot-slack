# npmdoc-hubot-slack

#### basic api documentation for  [hubot-slack (v4.3.4)](https://github.com/slackapi/hubot-slack#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-hubot-slack.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-hubot-slack) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-hubot-slack.svg)](https://travis-ci.org/npmdoc/node-npmdoc-hubot-slack)

#### A Slack adapter for hubot

[![NPM](https://nodei.co/npm/hubot-slack.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hubot-slack)

- [https://npmdoc.github.io/node-npmdoc-hubot-slack/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hubot-slack/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hubot-slack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hubot-slack/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-hubot-slack/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-hubot-slack/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Slack Technologies, Inc."
    },
    "bugs": {
        "url": "https://github.com/slackapi/hubot-slack/issues"
    },
    "contributors": [
        {
            "name": "Myles Grant"
        },
        {
            "name": "Evan Solomon"
        },
        {
            "name": "Jon Dalberg"
        },
        {
            "name": "Patrick Connolly"
        },
        {
            "name": "Chip Hayner"
        },
        {
            "name": "Eric Lindvall"
        },
        {
            "name": "D.E. Goodman-Wilson"
        },
        {
            "name": "John Agan"
        }
    ],
    "dependencies": {
        "@slack/client": "^3.4.0",
        "lodash": "^3.10.1"
    },
    "description": "A Slack adapter for hubot",
    "devDependencies": {
        "codecov": "~1.0.1",
        "coffee-coverage": "~1.0.1",
        "coffee-script": "~1.7.1",
        "grunt": "~0.4.1",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-watch": "~0.5.3",
        "grunt-release": "~0.6.0",
        "grunt-shell": "~0.5.0",
        "hubot": "~2.19",
        "istanbul": "^0.4.3",
        "mocha": "~1.13.0",
        "should": "~2.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "8b613b5458974905cc7454fb6eeaeda008efcf5c",
        "tarball": "https://registry.npmjs.org/hubot-slack/-/hubot-slack-4.3.4.tgz"
    },
    "engines": {
        "node": ">= 0.10.x",
        "npm": ">= 1.1.x"
    },
    "gitHead": "d9bb6990244831d38639496f6863730e26824d41",
    "homepage": "https://github.com/slackapi/hubot-slack#readme",
    "keywords": [
        "hubot",
        "tinyspeck",
        "adapter",
        "slack"
    ],
    "license": "MIT",
    "main": "./slack",
    "maintainers": [
        {
            "name": "aoberoi"
        },
        {
            "name": "grantmd"
        },
        {
            "name": "mjsz"
        },
        {
            "name": "paulhammond"
        },
        {
            "name": "roach"
        },
        {
            "name": "slackhq"
        }
    ],
    "name": "hubot-slack",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/slackapi/hubot-slack.git"
    },
    "scripts": {
        "codecov": "codecov",
        "mocha": "mocha --compilers coffee:coffee-script/register  --require coffee-coverage/register-istanbul --reporter spec test",
        "test": "npm run mocha && istanbul report text-summary lcov"
    },
    "version": "4.3.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
