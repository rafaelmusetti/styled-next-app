# Styled Next App

## Getting Started

### Requirements

For development, you will only need Node.js installed on your environement.

### Node

[Node](http://nodejs.org/) is really easy to install & now include [NPM](https://npmjs.org/).
You should be able to run the following command after the installation procedure
below.

    $ node --version
    v8.11.1

    $ npm --version
    5.6.0

### Installation

`npm install`

### Run

`npm run dev`

Then open [http://localhost:3000](http://localhost:3000). The start script is set to reload the app and keep the state just after a file is saved , no need for manual refresh.

### Build

`npm run build`

### Test

`npm run test`

[Jest](https://facebook.github.io/jest/docs/api.html) and [Enzyme](http://airbnb.io/enzyme/docs/api/) are the tools in place for unit testing the project code. Unit test files inside `__tests__` must be named with `*.test.js`.

### Folder structure and Suggested Workflow

This is the basic project folder structure

```javascript
...
  __tests__
  └──index.test.js // designed to contain the index page test
  pages // designed to contain all the pages of the application
    └──_app_.js // designed to contain styled-component theme
    └──_document_.js // designed to contain styled-component config
    └──index.js // designed to contain the index page
  ...
...
```

## Languages & tools

### JavaScript

- [Babel](https://babeljs.io/) is used as a JavaScript compiler and configurable transpiler.
- [React](http://facebook.github.io/react) is used for UI.
- [Next.js](https://nextjs.org/) is used to manipulate routes.
- [Jest](https://jestjs.io/) + [Enzyme](https://github.com/airbnb/enzyme) - is used for unit tests.
