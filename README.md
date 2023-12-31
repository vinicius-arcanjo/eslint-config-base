# ESLint config

## What's included?

- Standard config base
- React plugin
- React Hooks plugin
- Prettier

[//]: # (- JSX a11y plugin;)

## Setup

1. You need to create a `.npmrc` file and add the following lines:

```
registry=https://registry.npmjs.org/
@vinicius-arcanjo:registry=https://npm.pkg.github.com
```

2. Install the dependencies
```sh
# npm
npm i -D eslint @vinicius-arcanjo/eslint-config

# yarn
yarn add -D eslint @vinicius-arcanjo/eslint-config

# pnpm
pnpm add -D eslint @vinicius-arcanjo/eslint-config
```

3. Create a `.eslintrc.json` file extending the config to react:

```json
{
  "extends": "@vinicius-arcanjo/eslint-config/react"
}
```

or if it's node:

```json
{
   "extends": "@vinicius-arcanjo/eslint-config/node"
}
```

or if it's next:

```json
{
   "extends": "@vinicius-arcanjo/eslint-config/next"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.

## Contributing

Contributions are always welcome! If you wish to add new features or enhance the existing templates, please create a pull request to the appropriate branch.

## License

This project is under the [MIT License ©](https://github.com/vinicius-arcanjo/eslint-config-base/blob/main/LICENSE.md). See the `LICENSE` file in each branch for more details.
