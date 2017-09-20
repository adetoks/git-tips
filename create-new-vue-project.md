# Installation
Guide available at [Vue guide](https://vuejs.org/v2/guide/)

## NPM
NPM is the recommended installation method when building large scale applications with Vue. It pairs nicely with module bundlers such as Webpack or Browserify. Vue also provides accompanying tools for authoring Single File Components.
```
# latest stable
$ npm install vue
```

## CLI
Vue.js provides an official CLI for quickly scaffolding ambitious Single Page Applications. It provides batteries-included build setups for a modern frontend workflow. It takes only a few minutes to get up and running with hot-reload, lint-on-save, and production-ready builds:
```
# install vue-cli
$ npm install --global vue-cli
# create a new project using the "webpack" template
$ vue init webpack my-project
# install dependencies and go!
$ cd my-project
$ npm install
$ npm run dev
```

## Installing a simple Vue project

### Save Webpack package to packages.json

```
npm install webpack -s
```

### Install Webpack Command Tools Globally

```
npm install webpack -g
# Install into webpack commands into command line path
```

### Install Webpack and Vue Command Tools Globally

```
npm vue-cli -g
```

### Create a simple Vue and Webpack project

Once you've installed Webpack and Vue Command Tools Globally you can run the following command to scaffold a simple project with Webpack and Vue incorporated:

```
vue init webpack-simple
```

Once the scaffold has been made, run *npm install* to download all the packages into *node_modules* folder:

```
npm install
```

To then host the project on a local server in dev mode run:

```
npm run dev
```
