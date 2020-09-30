# chakracore-bin

**Deprecated. The [Node-ChakraCore](https://github.com/nodejs/node-chakracore) project has been archived.**

---

**Static [Node-ChakraCore](https://github.com/nodejs/node-chakracore#installing-prebuilt-node-chakracore-binaries) binaries to use locally.** Works like [node-bin](https://www.npmjs.com/node-bin).

[![npm version](https://img.shields.io/npm/v/chakracore-bin.svg)](https://www.npmjs.com/package/chakracore-bin)
![ISC-licensed](https://img.shields.io/github/license/derhuerst/chakracore-bin.svg)
[![chat on gitter](https://badges.gitter.im/derhuerst.svg)](https://gitter.im/derhuerst)


## Installing

This module uses [`download-chakracore`](https://github.com/derhuerst/download-chakracore) to download a ChakraCore release. Check its [requirements section](https://github.com/derhuerst/download-chakracore#requirements) first.

```shell
npm install chakracore-bin
```


## Usage

[npm scripts](https://docs.npmjs.com/cli/run-script) run with `node_modules/.bin` inside [`$PATH`](https://en.wikipedia.org/wiki/PATH_(variable)). This is what this `chakracore-bin` makes use of: It exposes ChakraCore as a `node` executable. To run your code with it, you therefore need to use an npm script:

```js
{
	"dependencies": {
		"node-chakracore": "^0.1.0"
	},
	"scripts": {
		"foo": "node index.js" // this will run with ChakraCore
	}
}
```


## Contributing

If you have a question or have difficulties using `chakracore-bin`, please double-check your code and setup first. If you think you have found a bug or want to propose a feature, refer to [the issues page](https://github.com/derhuerst/chakracore-bin/issues).
