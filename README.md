<div align="center" style="text-align: center;">
  <h1 style="border-bottom: none;">beatless-preview</h1>

  <p>Better greeting message</p>
</div>

<hr />

[![NPM][nodei-badge]][nodei-url]

[![Build Status][travis-badge]][travis-url]
[![Version][version-badge]][version-url]
[![Downloads][downloads-badge]][downloads-url]
[![MIT License][mit-license-badge]][mit-license-url]
[![Dependency Status][daviddm-badge]][daviddm-url]
[![NSP Status][nsp-badge]][nsp-url]

[![Code of Conduct][coc-badge]][coc-url]

[![codebeat-badge]][codebeat-url]
[![codacy-badge]][codacy-url]
[![inch-badge]][inch-url]

> Next episode previews of the anime Beatless

## Table of contents

- [Pre-requisite](#pre-requisite)
- [Setup](#setup)
  - [Install](#install)
  - [Usage](#usage)
    - [Node.js](#nodejs)
    - [Native ES modules or TypeScript](#native-es-modules-or-typescript)
- [API Reference](#api-reference)
  - [greeting(name)](#greetingname)
  - [greetingSync(name)](#greetingsyncname)
- [License](#license)

## Pre-requisites

- [Node.js][node-js-url] >= 8.9.0
- [NPM][npm-url] >= 5.5.1 ([NPM][npm-url] comes with [Node.js][node-js-url] so there is no need to install separately.)

## Setup

### Install

```sh
# Install via NPM
$ npm install --save beatless-preview
```

### Usage

#### Node.js

```js
const greeting = require('beatless-preview');
```

#### Native ES modules or TypeScript

```ts
// @ts-check

import greeting from 'beatless-preview';
```

## API Reference

### greeting(name)

  - name <[string][string-mdn-url]> Name of the person to greet at.
  - returns: <[Promise][promise-mdn-url]&lt;[string][string-mdn-url]&gt;> Promise which resolves with a greeting message.

### greetingSync(name)

This methods works the same as `greeting(name)` except that this is the synchronous version.

## License

[MIT License](https://motss.mit-license.org/) © Rong Sen Ng



[typescript-url]: https://github.com/Microsoft/TypeScript
[node-js-url]: https://nodejs.org
[npm-url]: https://www.npmjs.com
[node-releases-url]: https://nodejs.org/en/download/releases

[array-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
[boolean-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean
[function-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function
[map-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map
[number-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number
[object-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object
[promise-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise
[regexp-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp
[set-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set
[string-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String



[nodei-badge]: https://nodei.co/npm/beatless-preview.png?downloads=true&downloadRank=true&stars=true

[travis-badge]: https://img.shields.io/travis/motss/beatless-preview.svg?style=flat-square

[version-badge]: https://img.shields.io/npm/v/beatless-preview.svg?style=flat-square
[downloads-badge]: https://img.shields.io/npm/dm/beatless-preview.svg?style=flat-square
[mit-license-badge]: https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square
[nsp-badge]: https://nodesecurity.io/orgs/motss/projects/a1c57ec8-9c17-4912-932b-f1ff6284e2ae/badge?style=flat-square
[daviddm-badge]: https://img.shields.io/david/motss/beatless-preview.svg?style=flat-square

[coc-badge]: https://img.shields.io/badge/code%20of-conduct-ff69b4.svg?style=flat-square

[codebeat-badge]: https://codebeat.co/badges/e486e791-12b7-4198-b834-0fa5bd04e1c3?style=flat-square
[codacy-badge]: https://api.codacy.com/project/badge/Grade/a70d1556b4e74711a162c4fd4dbb68a1?style=flat-square
[inch-badge]: http://inch-ci.org/github/motss/beatless-preview.svg?branch=master&style=flat-square



[nodei-url]: https://nodei.co/npm/beatless-preview

[travis-url]: https://travis-ci.org/motss/beatless-preview
[version-url]: https://npmjs.org/package/beatless-preview
[downloads-url]: http://www.npmtrends.com/beatless-preview
[mit-license-url]: https://github.com/motss/beatless-preview/blob/master/LICENSE
[nsp-url]: https://nodesecurity.io/orgs/motss/projects/a1c57ec8-9c17-4912-932b-f1ff6284e2ae
[daviddm-url]: https://david-dm.org/motss/beatless-preview

[coc-url]: https://github.com/motss/beatless-preview/blob/master/CODE_OF_CONDUCT.md

[codebeat-url]: https://codebeat.co/projects/github-com-motss-beatless-preview-master
[codacy-url]: https://www.codacy.com/app/motss/beatless-preview?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=motss/beatless-preview&amp;utm_campaign=Badge_Grade
[inch-url]: http://inch-ci.org/github/motss/beatless-preview
