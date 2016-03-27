# cyc

[![https://img.shields.io/npm/v/cyc-cli.svg?style=flat-square](https://img.shields.io/npm/v/cyc-cli.svg?style=flat-square)](https://www.npmjs.com/package/cyc-cli)
[![https://img.shields.io/npm/dt/cyc-cli.svg?style=flat-square](https://img.shields.io/npm/dt/cyc-cli.svg?style=flat-square)](https://www.npmjs.com/package/cyc-cli)
[![https://img.shields.io/npm/l/cyc-cli.svg?style=flat-square](https://img.shields.io/npm/l/cyc-cli.svg?style=flat-square)](https://www.npmjs.com/package/cyc-cli)

*cyc* provides an intuitive and hassle-free starting point for Cycle.js applications. It comes with production and development webpack configurations, dynamic hot reloading, Babel transpilation, unintrusive long-term caching, and an isomorphic express server. The *cyc* boilerplate is scalable, convenient, and highly modular.

[View the live preview.](http://edge.github.io/cyc/)

## Features
- production and development webpack configurations
- project-wide babel transpilation
- hot reloading with cycle-restart
- dynamic isomorphic loading with dynamic-require
- declarative server endpoints
- long-term caching

## Installing

```sh
$ npm install -g cyc-cli babel-cli
```

## Creating a Project

```sh
$ cyc
  Application Name myapp
  Directory (myapp)
  Copying...
  Populating...
  Done.
$ cd myapp
$ npm i
```

## Running a Project

**Development**
```sh
$ npm run dev
```

**Production**
```sh
$ npm run mk
$ PORT=80 npm start
```

## npm scripts

Unix:
- `dev` start dev server
- `start` start production server (requires built server and client)
- `mkserver` build production server (fast)
- `mkclient` build production client (slow)
- `mk` build production server and client

Windows:
- put `w` before any command listed above (e.g. `wdev`)
