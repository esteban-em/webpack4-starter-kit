# webpack4-starter-kit

Webpack 4 with webpack-dev-server configuration (and Web Components).

## Requirements

- Node >= v6.x
- Yarn >= v1.1 | NPM >= v5.0

## Installation via CLI

  * Install w4kit-cli

```
npm install -g w4kit-cli
```

  * launch the CLI

```
w4kit
```

## Installation via Clone

* Clone this repository

```
git clone https://github.com/king-prawns/webpack4-starter-kit.git [your-app-name]
```

Remove the .git folder and change details within:

```
package.json
src/manifest.json
```

* Install dependencies

```
$ cd my-app-name
$ yarn
```

## Available tasks

```sh

# Runs development server (Webpack dev server)
$ yarn dev

# Build command
$ yarn build

# Lint with ESLint
$ yarn lint

# Run Flow
$ yarn flow

# Run unit tests (ava + instanbul)
$ yarn test

# Runs http-server on port 8082
$ yarn httpserver

```

## Features

* [Webpack 4](https://github.com/webpack/webpack)
* [Webpack Dev Server](https://github.com/webpack/webpack-dev-server)
* [HMR](https://webpack.js.org/concepts/hot-module-replacement/)
* [Babel](https://babeljs.io/)
* [Flow](https://flow.org/)
* [EsLint](https://eslint.org/docs/user-guide/getting-started)
* [StyleLint](https://github.com/stylelint/stylelint)
* [Sass](https://github.com/webpack-contrib/sass-loader)
* [Autoprefixer](https://github.com/postcss/autoprefixer)
* [Ava](https://github.com/avajs/ava)
* [nyc](https://github.com/istanbuljs/nyc)
* [Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components)
* [Service Worker](https://github.com/NekR/offline-plugin)
* Webpack Plugins: Html, Copy, ExtractText, Define

## TypeScript

### PLEASE GO TO [TS BRANCH](https://github.com/king-prawns/webpack4-starter-kit/tree/typescript)
