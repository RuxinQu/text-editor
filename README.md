# text-editor

![Node](https://img.shields.io/badge/-Node.js-darkgreen)
![Express](https://img.shields.io/badge/-Express-black) 
![webpack](https://img.shields.io/badge/-webpack-blue) 
![Heroku](https://img.shields.io/badge/-Heroku-purple) 
![MIT license](https://img.shields.io/badge/License-MIT-green.svg)
![badge](https://img.shields.io/github/languages/top/ruxinqu/text-editor)

## Description

This progressive web application allows users to create notes or code snippets with or without an internet connection. Users can also install the app. The files have been bundled using [webpack](https://webpack.js.org). The manifest.json is generated using [webpack-pwa-manifest](https://www.npmjs.com/package/webpack-pwa-manifest) package. The data is stored using [idb](https://www.npmjs.com/package/idb) package. 

View the deployed website: https://text-editor-rq.herokuapp.com

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Technologies Used](#technologies-used)
- [Question](#question)

## Installation

1. Run `git@github.com:RuxinQu/text-editor.git` on the terminal to git clone the repo.
2. Then run `npm install` to download all the packages.

## Usage
1. Run `npm start` to start the app
2. Enter some text and it'll be saved with indexedDB
3. Refresh the browser the text will be retrieved from indexedDB
4. Install the app and the registered service worker will render the precached assets

The video below demonstrates the application functionality:

![demo video](./assets/text-editor.gif)

## License

This project is under MIT license

[https://opensource.org/licenses/MIT](https://opensource.org/lsicenses/MIT)

## Technologies Used


- [express](https://expressjs.com)
- [idb](https://www.npmjs.com/package/idb)
- [webpack](https://webpack.js.org)
- [webpack-pwa-manifest](https://www.npmjs.com/package/webpack-pwa-manifest)
- [heroku](https://heroku.com)

## Question

 Contact me via: ruxinqu@gmail.com if you have addition questions.
