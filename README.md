# eslint-config-react-native-chris24elias

My ESLint and TypeScript configuration for React Native.

[![npm version](https://badge.fury.io/js/eslint-config-react-native-chris24elias.svg)](https://badge.fury.io/js/eslint-config-react-native-chris24elias)

## Usage

```sh
# you also need eslint if not installed already: yarn add eslint --dev
yarn add eslint-config-react-native-chris24elias --dev
```

In `.eslintrc`:

```json
{
  "extends": "react-native-chris24elias"
}
```

In `tsconfig.json` (if you want to use my base TS configuration):

```json
{
  "extends": "eslint-config-react-native-chris24elias/tsconfig.base"
}
```
