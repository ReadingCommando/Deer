## Development dependencies

Packages which are used during development or which are used to build Deer's bundle. These packages are necessary **only** while you are developing Deer.

|           Name          |  Version  |    Usage   |
| ----------------------- | --------- | ---------- |
| babel-core              | ^6.26.3   | Needed for other babel's packages |
| babel-loader            | ^7.1.4    | A Webpack loader responsible for taking in the ES6 code and making it understandable |
| babel-plugin-transform-object-rest-spread | ^6.26.0 | A Babel plugin responsible for transforming rest and spread properties for objects |
| babel-preset-env        | ^1.7.0    | A Babel plugin responsible for compiling Javascript ES6 code down to ES5 |
| babel-preset-react      | ^6.24.1   | A Babel plugin responsible for compiling JSX down to Javascript |
| css-loader              | ^0.28.11  | A Webpack loader responsible for collecting CSS from all the css files and put it into a string |
| electron-reload         | ^1.2.2    | Reload contents of when the source files are changed |
| eslint                  | ^4.19.1   | Linting utility for JavaScript and JSX |
| eslint-config-standard  | ^11.0.0   | JavaScript Standard Style |
| eslint-config-standard-react  | ^6.0.0   | JavaScript Standard Style React/JSX support |
| eslint-plugin-import    | ^2.12.0   | Support linting of ES2015+ (ES6+) import/export syntax |
| eslint-plugin-node      | ^6.0.1    | ESLint's rules for Node.js |
| eslint-plugin-promise   | ^3.8.0    | Enforce best practices for JavaScript promises |
| eslint-plugin-react     | ^7.9.1    | React specific linting rules for ESLint |
| eslint-plugin-standard  | ^3.1.0    | ESlint Plugin for the Standard Linter |
| file-loader             | ^1.1.11   | A Webpack loader responsible for emitting files that will be bundled and returning their public URLs (e.g. Images) |
| husky                   | ^0.14.3   | Prevent bad commit, push by doing checks before it takes place |
| style-loader            | ^0.21.0   | A Webpack loader responsibile for taking the output string generated by by css-loader and put it inside the <style> tags |
| webpack                 | ^4.12.0   | A module bundler for JavaScript files |
| webpack-cli             | ^3.0.3    | Required by web pack |

## Production dependencies

Packages which are required at runtime. These packages are essential for Deer to work
Those are dependencies that are essential for software to work.

|          Name         |    Version    |    Usage   |
| --------------------- | ------------- | ---------- |
| bootstrap             | ^4.1.1        | A front-end framework |
| electron              | ^2.0.2        | Build cross platform desktop apps |
| electron-is-dev       | ^0.3.0        | Check if Electron is running in development |
| electron-log          | ^2.2.15       | A multi-transport async logging library |
| electron-store        | ^2.0.0        | Save and load user preferences |
| electron-window-state | ^4.1.1        | Store and restore window sizes and positions |
| pouchdb-browser       | ^6.4.3        | A pocket-sized database. |
| prop-types            | ^15.6.1       | A Runtime type checking for React props |
| react                 | ^16.4.0       | A JavaScript library for building user interfaces |
| react-dom             | ^16.4.0       | React package for working with the DOM |
| react-redux           | ^5.0.7        | React bindings for Redux |
| react-router-dom      | ^4.3.1        | A DOM bindings for React Router |
| reactstrap            | ^6.1.0        | A Stateless React Components for Bootstrap 4 |
| redux                 | ^4.0.0        | A predictable state container for JavaScript apps |
| redux-actions         | ^2.4.0        | Helpers for both handling and creating actions |
| redux-thunk           | ^2.3.0        | A Redux middleware allows writing asynchronous actions |

## References

[package.json: Specifics of npm's package.json handling](https://docs.npmjs.com/files/package.json)

[Rest and spread properties](https://babeljs.io/docs/en/babel-plugin-transform-object-rest-spread/)