# React Template

This repository contains a template for React applications.

<br>

## Table of Contents
   - [Getting Started](#getting-started)
   - [Dependencies](#dependencies)

<br>

## Getting Started

1. Clone the repository.
   ```
   git clone https://github.com/kevinydhan/react-babel-webpack-eslint-template.git
   ```

2. Install the dependencies.
   ```
   npm i
   ```
   
   or 
   
   ```
   yarn
   ```

3. Start developing!
   ```
   npm run dev
   ```
   
   or 
   
   ```
   yarn dev
   ```

<br>

## Dependencies

Below are explanations regarding why certain packages were used:

| Dependency | Usage | 
| :-- | :-- |
| [`prop-types`][100] | Used to check types for React props at runtime |
| [`react`][101] | Used to build the HTML and Javascript | 
| [`react-dom`][102] | Used to render the React application |

<br>

| Dev Dependency | Usage | 
| :-- | :-- |
| [`@babel/core`][200] | Additional dependency for `babel-loader` | 
| [`@babel/plugin-proposal-class-properties`][201] | Enables class properties syntax |
| [`@babel/preset-env`][202] | Allows the usage of the latest JavaScript without needing to micromanage which syntax transforms are needed by your target environment |
| [`@babel/preset-react`][203] | Additional dependency for transpiling React code |
| [`babel-eslint`][204] | Allows ESLint to understand JSX |
| [`babel-loader`][205] | Allows transpiling of JavaScript files using Babel and Webpack |
| [`eslint`][206] | Used to perform linting on the codebase |
| [`eslint-config-prettier`][207] | Turns off all rules that are unnecessary or might conflict with Prettier |
| [`eslint-plugin-babel`][208] | Additional ESLint plugin for `babel-eslint` |
| [`eslint-plugin-html`][209] | Used to lint HTML files |
| [`eslint-plugin-prettier`][210] | Runs Prettier as an ESLint rule and reports differences as individual ESLint issues |
| [`eslint-plugin-react`][211] | Introduces React-specific ESLint rules |
| [`lite-server`][212] | Spins a development server that serves `/public` |
| [`prettier`][213] | Code formatter |
| [`webpack`][214] | Used to bundle the React application |
| [`webpack-cli`][215] | Enables Webpack command line interface |

[100]: https://github.com/facebook/prop-types
[101]: https://reactjs.org/docs/getting-started.html
[102]: https://reactjs.org/docs/react-dom.html

[200]: https://babeljs.io/docs/en/babel-core
[201]: https://babeljs.io/docs/en/babel-plugin-proposal-class-properties
[202]: https://babeljs.io/docs/en/babel-preset-env
[203]: https://babeljs.io/docs/en/babel-preset-react
[204]: https://github.com/babel/babel-eslint
[205]: https://github.com/babel/babel-loader
[206]: https://eslint.org/docs/user-guide/getting-started
[207]: https://github.com/prettier/eslint-config-prettier
[208]: https://github.com/babel/eslint-plugin-babel
[209]: https://github.com/BenoitZugmeyer/eslint-plugin-html
[210]: https://github.com/prettier/eslint-plugin-prettier
[211]: https://github.com/yannickcr/eslint-plugin-react
[212]: https://github.com/johnpapa/lite-server
[213]: https://prettier.io/docs/en/index.html
[214]: https://webpack.js.org/concepts
[215]: https://webpack.js.org/api/cli
