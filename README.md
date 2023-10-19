# cypress-fe-testing-biolerplate

This is a Typescript Cypress boilerplate framework with ESLint setup to enforce coding format and structure. 

- [cypress-fe-testing-biolerplate](#cypress-fe-testing-biolerplate)
  - [Dependencies](#dependencies)
  - [Folder File Structure](#folder-file-structure)
  - [Cypress Typescript](#cypress-typescript)
  - [Run Tests](#run-tests)
    - [Example Test](#example-test)
  - [ESLint](#eslint)
    - [Prettier](#prettier)

## Dependencies
- [NodeJS](https://nodejs.org/en/download/) (Version 18, note the project was setup on Node v18.18.0)
- [Yarn](https://yarnpkg.com/getting-started/install) 
- [Google Chrome](https://www.google.com/chrome/)

## Folder File Structure
- [`./cypress`](./cypress) - Folder containing cypress files
- [`./cypress/e2e`](./cypress/e2e) - Folder containing test suites
- [`./cypress.config.js`](./cypress.config.js) - Cypress config file

## Cypress Typescript
This is a Cypress project that is using Typescript, setup as explained in [Cypress documentation](https://docs.cypress.io/guides/tooling/typescript-support#Install-TypeScript). The test files should use Typescript and the `.ts` extension. 

## Run Tests
To run all the tests use the command the following command.

```bash
yarn test
```

If you want to open Cypress to configure or run individual tests you can use the following command.

```bash
yarn cypress open
```

### Example Test
You can find an example test at [`./cypress/e2e/exampleTest.cy.ts`](./cypress/e2e/exampleTest.cy.ts)

## ESLint
This project supports ESLint and can be run using the following command.

```bash
yarn lint
```

If you want ESLint to try to fix errors you can run the following command.

```bash
yarn lint --fix
```

### Prettier
ESLint also uses prettier to enforce code formatting (Tabs, Colons, etc.)