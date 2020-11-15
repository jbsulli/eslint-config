# ESLint

Repository of configs

## ESLint & Prettier

```
yarn add --dev eslint prettier @jbsulli/eslint-config@*
```

Example `package.json`:
```json
{
  "name": "my-app",
  "prettier": "@jbsulli/eslint-config/prettier.yml",
  "eslintConfig": {
    "extends": ["@jbsulli"]
  },
  "devDependencies": {
    "@jbsulli/eslint-config": "*",
    "eslint": "^7.13.0",
    "prettier": "^2.1.2"
  }
}
```
