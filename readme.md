# @novas/eslint-config

ESLint config for ES2021 and TypeScript

## Installation

To use in your own custom configuration, install then extend this package in your ESLint config:

1. Install dependencies
```sh
yarn add --dev @novas/eslint-config @babel/eslint-parser @babel/eslint-plugin @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-prettier eslint-plugin-react eslint-plugin-react-hooks typescript 
```
Note: Due to the way ESLint `overrides` work, Typescript `devDependencies` are required regardless of whether you are using Typescript in your project.

2. Configure ESLint
```jsonc
// .eslintrc
{
    "extends": ["@novas/eslint-config"]
}
```
