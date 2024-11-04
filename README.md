# Electron Forge App with Vite-Vue

This template app should help get you started developing Electron App (Forge) with Vue 3 in Vite. This is created from `npm init electron-app@latest XXX -- --template=vite-typescript` and merged vue parts from `yarn create vue`.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
yarn
```

### Electron Forge - Starting your app

```sh
yarn start
```

### Electron Forge - Building distributables

```sh
yarn make
```

### Electron Forge - Publishing your app

```sh
yarn publish
```

### Vite-Vue - Compile and Hot-Reload for Development

```sh
yarn dev
```

### Vite-Vue - Type-Check, Compile and Minify for Production

```sh
yarn build
```

### Vite-Vue - Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
yarn test:unit
```

### Vite-Vue - Run End-to-End Tests with [Cypress](https://www.cypress.io/)

```sh
yarn test:e2e:dev
```

This runs the end-to-end tests against the Vite development server.
It is much faster than the production build.

But it's still recommended to test the production build with `test:e2e` before deploying (e.g. in CI environments):

```sh
yarn build
yarn test:e2e
```

### Vite-Vue - Lint with [ESLint](https://eslint.org/)

```sh
yarn lint
```

## Contact
zegang.luo@qq.com
