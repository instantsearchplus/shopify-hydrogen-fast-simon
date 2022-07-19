# Fast Simon & Shopify Integration

Build Search and Discovery experience with Fast Simon, a Shopify Plus Certified Partner

[Getting started guide](https://instantsearchplus.zendesk.com/hc/en-us/categories/360000839131-Getting-Started-with-Fast-Simon)

# Hydrogen App

Hydrogen is a React framework and SDK that you can use to build fast and dynamic Shopify custom storefronts.

[Check out the docs](https://shopify.dev/custom-storefronts/hydrogen)


### Configuration for Hydrogen & Fast Simon

* Hydrogen

Update `hydrogen.config.js` with your shop's domain and Storefront API token.

* Fast Simon

Update fastsimon.config.json with your Fast Simon UUID & store id.


### Template features

* Fast Simon Autocomplete search
  
* End-to-end testing with [Playwright](https://playwright.dev)

* Unit testing with [Vitest](https://vitest.dev) and [Testing Library](https://testing-library.com)

* Code formatting with [Prettier](https://prettier.io)

* Javascript linting with [ESLint](https://eslint.org) and the Hydrogen [ESLint plugin](https://github.com/Shopify/hydrogen/tree/main/packages/eslint-plugin)


### Getting started

**Requirements:**

- Node.js version 16.5.0 or higher
- Yarn

```bash
yarn
yarn dev
```

### Previewing a production build

To run a local preview of your Hydrogen app in an environment similar to Oxygen, build your Hydrogen app and then run `yarn preview`:

```bash
yarn build
yarn preview
```

### Building for production

```bash
yarn build
```