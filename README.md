# ESLint config

## What's included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- Prettier;

[//]: # (- JSX a11y plugin;)

## Setup

1. Install the dependencies
```sh
# npm
npm i -D eslint @vinicius-arcanjo/eslint-config

# yarn
yarn add -D eslint @vinicius-arcanjo/eslint-config

# pnpm
pnpm add -D eslint @vinicius-arcanjo/eslint-config
```

For `pnpm` you need to create a `.npmrc` file and add the following lines:

```
registry=https://registry.npmjs.org/
@vinicius-arcanjo:registry=https://npm.pkg.github.com
```

2. Create a `.eslintrc.json` file extending the config to react:

```json
{
  "extends": "@vinicius-arcanjo/eslint-config/react"
}
```

or if it's node:

```json
{
   "extends": "@azul-tecnologia/eslint-config/node"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.
