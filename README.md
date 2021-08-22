<div align="center">
<h1>Vue 2 Starter</h1>
<p>This starter was created as a starting template for a Vue.js 2 frontend application built with TypeScript.</p>
</div>

## Features

- [TypeScript](https://www.typescriptlang.org/) - For type safety and other awesome features not native to vanilla JavaScript.
- [SASS](https://sass-lang.com/) - CSS extension language for CSS nesting, mixins, variables, modules and inheritance.
- [BEM Methodology](http://getbem.com/) - Methodology for naming and organizing CSS selectors and HTML elements.
- [Vuex](https://vuex.vuejs.org/) - Vue.js library for state management.

## Roadmap

- [x] Unit tests with mocha, chai & sinon
- [ ] Continuous integration with TravisCI
- [ ] Coverage reports with Istanbul & Coveralls
- [ ] Add SCSS files with [7-1 architecture pattern](https://sass-guidelin.es/#the-7-1-pattern)
- [ ] Containerized setup with docker-compose

## Environment Variables

To begin using the starter project, first copy the example variables into a `.env.[mode].local` file with command: `cp .env.example .env.[mode].local`. The modes available are [documented here](https://cli.vuejs.org/guide/mode-and-env.html#modes). You will then need to modify the following environment variables in the `.env.[mode].local` file for your frontend to run:

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

Tests are written in Mocha, Chai under the `tests` directory and uses `istanbul` for coverage reports. To run tests, run the following command

```bash
  npm run test:unit
```

To run and view coverage reports for the tests, you will need to run two scripts in sequential order

```bash
  npm run test:coverage ; npm run test:view
```

## Linting

Linting is configured with eslint and prettier. You are free to configure it to your liking using the configuration file `.eslintrc.js`.

To check for and fix linting errors, run

```bash
  npm run lint
```

## Further Customization

See [configuration reference here](https://cli.vuejs.org/config/) for further customization

## Authors

[Peter Kitonga](https://www.github.com/peterkitonga)
