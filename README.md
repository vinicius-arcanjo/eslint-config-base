# ESLint config

## What's included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- Prettier;

[//]: # (- JSX a11y plugin;)

## Setup

1. Install the dependencies
```
npm i -D eslint @azul-tecnologia/eslint-config
```

2. Create a `.eslintrc.json` file extending the config:
```
{
  "extends": "@azul-tecnologia/eslint-config/react"
  // "extends": "@azul-tecnologia/eslint-config/node"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.
