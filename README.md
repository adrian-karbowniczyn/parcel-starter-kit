# Parcel starter kit
Starter kit based on **[parcel bundler](https://parceljs.org/)**, used for web development 👩‍💻

![Cover image.](./cover-image.png)

## Table of content
* [About the Project](#about-the-project)
* [Requirement](#requirement)
* [Getting Started](#getting-started)
* [Usage](#usage)
* [Project tree](#project-tree)
* [Acknowledgements](#acknowledgements)
* [Used packages](#used-packages)

## About this Project 
I've created this template 📓 to speed up creation of the projects, installing all the necessery packages, writing scripts, creating file structure 📂 can be time consuming and annoying 🤯 This template will help you with that 😎

## Requirement

If you don't have already installed **[Node.js](https://nodejs.org/en/)** and **[yarn](https://yarnpkg.com/)** just do it now !

## Getting Started

Click on `Use this template` button and follow instructions, clone your repo on your computer, go to the project folder and in console type `yarn install`. Yarn will install all needed packages after that you are ready to code 👨‍💻

## Usage 🔧

`yarn dev` - runs development mode

`yarn build` - runs build process for production

`yarn test` - runs jest tests

`yarn test:report` - build coverage report

`yarn lint` - runs eslinter

`yarn lint:fix` - runs eslint and trying to the fix errors

`yarn publish` - runs build and publish the page using `gh-pages` branch

## Project tree 🌳
```
.
├── node_modules
├── src
│   ├── tests
│   ├── assets
│   │   └── images
│   │       └── icons
│   ├── sass
│   │   ├── layout
│   │   ├── base
│   │   │   ├── _typography.scss
│   │   │   ├── _variables.scss
│   │   │   └── _reset.scss
│   │   ├── main.scss
│   │   ├── components
│   │   └── pages
│   ├── js
│   │   └── index.js
│   └── pages
│       └── index.html
├── babel.config.js
├── package.json
├── cover-image.png
├── jest.config.js
├── README.md
└── yarn.lock
```

## Acknowledgements 📖

* [Yarn - docs](https://classic.yarnpkg.com/en/docs/)
* [Prettier](https://prettier.io/)
* [Eslint](https://eslint.org/)
* [Getting Prettier, Eslint and Vscode to work together](https://dev.to/chgldev/getting-prettier-eslint-and-vscode-to-work-together-3678)
* [What is Babel?](https://babeljs.io/docs/en/)
* [Parcel - Getting Started](https://parceljs.org/getting_started.html)
* [Jest - Getting Started](https://jestjs.io/docs/en/getting-started)
* [Sass](https://sass-lang.com/)

## Used packages 📦
* @babel/core
* @babel/preset-env
* babel-jest
* eslint
* eslint-config-airbnb-base
* eslint-config-prettier
* eslint-plugin-import
* eslint-plugin-prettier
* jest
* parcel
* prettier
* sass
* gh-pages