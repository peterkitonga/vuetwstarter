<div align="center">
<h1>Vue 2 Starter</h1>
<p>This starter was created as a starting template for a Vue.js 2 frontend application built with TypeScript.</p>
</div>

## Features

- [TypeScript](https://www.typescriptlang.org/) - For type safety and other awesome features not native to vanilla JavaScript.
- [SASS](https://sass-lang.com/) - CSS extension language for CSS nesting, mixins, variables, modules and inheritance.
- [BEM Methodology](http://getbem.com/) - Methodology for naming and organizing CSS selectors and HTML elements.
- [Vuex](https://vuex.vuejs.org/) - Vue.js library for state management.

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

- `VUE_APP_NAME` - Name of the application

- `VUE_APP_URI` - URI for the application

- `VUE_APP_API_URI` - URI for the REST API

## Run Locally

Clone the project

```bash
  git clone https://github.com/peterkitonga/vuetwstarter
```

Go to the project directory

```bash
  cd vuetwstarter
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run serve
```

## Deployment

Install dependencies first

```bash
  npm install
```

To deploy this project run

```bash
  npm run build
```

## Running Tests

Tests are written in Mocha, Chai under the `test` directory and uses `istanbul` for coverage reports. To run tests, run the following command

```bash
  npm run test:unit
```

## Linting

Linting is configured with eslint and prettier. You are free to configure it to your liking using the configuration files `.eslintrc.js` and `.prettierrc.js`

To check for and fix linting errors, run

```bash
  npm run lint
```

## Further Customization

See [Configuration Reference](https://cli.vuejs.org/config/) for further customization

## Authors

[Peter Kitonga](https://www.github.com/peterkitonga)
