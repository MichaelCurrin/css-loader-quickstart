# CSS Loader Quickstart
> Starter template for using CSS Loader and Webpack

![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/css-loader-quickstart?include_prereleases=&sort=semver)](https://github.com/MichaelCurrin/css-loader-quickstart/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Package - webpack](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/css-loader-quickstart/webpack)](https://www.npmjs.com/package/webpack)
[![Package - css-loader](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/css-loader-quickstart/css-loader)](https://www.npmjs.com/package/css-loader)
[![Package - style-loader](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/css-loader-quickstart/style-loader)](https://www.npmjs.com/package/style-loader)


## Installation

Install Node.js.

Clone the repo.

Install project packages with:

```sh
$ npm install
```


## Usage

### Watch

Bundle the JS and CSS with webpack. This will watch continuously.

```sh
$ npm start
```

Then open a dev server in the `dist` directory and open localhost in your browser.

### Build

Do a build and then stop.

```sh
$ npm run build
```

You might want to switch to using production settings in the Webpack config.


## About

### Dependencies

- Webpack
    - https://webpack.js.org/
- CSS Loader
    - https://github.com/webpack-contrib/css-loader
    - Using default config settings from README
- Style Loader
    - https://webpack.js.org/loaders/style-loader/
    - Must be installed since that it is the config
- Sanitize CSS
    - https://csstools.github.io/sanitize.css/

### Set up

Set the dependencies up in a fresh project with:

```sh
$ npm i -D webpack webpack-cli css-loader style-loader
$ npm i sanitize.css
```


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).
