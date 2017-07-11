# typesync

Install missing TypeScript typings for dependencies in your `package.json`.

[![npm](https://img.shields.io/npm/v/typesync.svg?maxAge=1000)](https://www.npmjs.com/package/typesync)
[![dependency Status](https://img.shields.io/david/jeffijoe/typesync.svg?maxAge=1000)](https://david-dm.org/jeffijoe/typesync)
[![devDependency Status](https://img.shields.io/david/dev/jeffijoe/typesync.svg?maxAge=1000)](https://david-dm.org/jeffijoe/typesync)
[![Build Status](https://img.shields.io/travis/jeffijoe/typesync.svg?maxAge=1000)](https://travis-ci.org/jeffijoe/typesync)
[![Coveralls](https://img.shields.io/coveralls/jeffijoe/typesync.svg?maxAge=1000)](https://coveralls.io/github/jeffijoe/typesync)
[![npm](https://img.shields.io/npm/dt/typesync.svg?maxAge=1000)](https://www.npmjs.com/package/typesync)
[![npm](https://img.shields.io/npm/l/typesync.svg?maxAge=1000)](https://github.com/jeffijoe/typesync/blob/master/LICENSE.md)
[![node](https://img.shields.io/node/v/typesync.svg?maxAge=1000)](https://www.npmjs.com/package/typesync)

# Install

```
npm install -g typesync
```

# Usage

```
typesync [path/to/package.json]
```

Path is relative to the current working directory. If omitted, defaults to `package.json`.

# Why?

Installing typings manually sucks. Flow has `flow-typed` which installs type definitions by looking at a `package.json`, which would be cool to have for TypeScript.

# Author

Jeff Hansen - [@Jeffijoe](https://twitter.com/jeffijoe)
