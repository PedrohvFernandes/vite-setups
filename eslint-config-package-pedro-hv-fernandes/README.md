# ESLint config  <img src="https://img.shields.io/badge/eslint-3A33D1?style=for-the-badge&logo=eslint&logoColor=white">

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

### React (Vite or CRA)

Install dependencies:
```
npm i -D eslint @pedrohvfernandes/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@pedrohvfernandes/eslint-config/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint @pedrohvfernandes/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@pedrohvfernandes/eslint-config/node"
}
```