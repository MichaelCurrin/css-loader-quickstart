# CSS Loader Quickstart
> Starter template for using CSS Loader and Webpack

[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/css-loader-quickstart?include_prereleases=&sort=semver)](https://github.com/MichaelCurrin/css-loader-quickstart/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Made with Node.js](https://img.shields.io/badge/Node.js->=12-blue?logo=node.js&logoColor=white)](https://nodejs.org)

[![Package - webpack](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/css-loader-quickstart/dev/webpack)](https://www.npmjs.com/package/webpack)
[![Package - css-loader](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/css-loader-quickstart/dev/css-loader)](https://www.npmjs.com/package/css-loader)
[![Package - style-loader](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/css-loader-quickstart/dev/style-loader)](https://www.npmjs.com/package/style-loader)


## Use this project

<div align="center">

[![Use this template](https://img.shields.io/badge/Generate-Use_this_template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/css-loader-quickstart/generate)

</div>


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

## How it works

When running Webpack the JS file [index.js](/src/index.js) and styling imports gt bundled as a single JS file. In particular, there is a local CSS file ([styles.css](/src/styles.css)) and an installed CSS dependency (`sanitize.css`).

The CSS gets added to the JS because of two CSS loading dependencies that are installed and also because Webpack is configured to use those dependencies for CSS files. See [webpack.config.js](/webpack.config.js).

When the bundled JS file (`bundle.js`) gets loaded on the frontend, the JS will inserted the CSS into the DOM for you. So you don't need to add a style or link tag yourself.

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
