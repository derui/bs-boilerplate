# Boilerplate for Bucklescript #
This repository provides boilerplate for bucklescript. Save time to select and decide packages.

- bs-platform 2.0.0
- Webpack 3.8.x
  - only used for unit test
- Karma 1.7.x
  - + Headless chrome + mocha
  - only used for unit test
- Format all OCaml files
  - Use ocp-indent, so require it

## Required ##

- nodejs 8.x
- OCaml compiler for Bucklescript
  - should use **opam** to install it
- ocp-indent

## Install ##

```shell
$ git clone https://github.com/derui/bs-boilerplate.git sample
$ cd sample
$ npm i
```

## Build ##

```
npm run build
```

## Watch ##

```
npm run watch
```

## Test ##

```
npm run test
```

## Editor ##

If you use `vscode`, Press `Windows + Shift + B` it will build automatically
