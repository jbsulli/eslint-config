# ESLint

Repository of configs

## ESLint & Prettier

```
yarn add --dev eslint prettier @jbsulli/config
```

Example `package.json`:
```json
{
  "name": "my-app",
  "prettier": "@jbsulli/config/prettier",
  "eslintConfig": {
    "extends": ["@jbsulli/config/eslint"]
  },
  "devDependencies": {
    "@jbsulli/config": "*",
    "eslint": "^7.13.0",
    "prettier": "^2.1.2"
  }
}
```
