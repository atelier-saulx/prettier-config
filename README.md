# prettier-config
Our prettier config. Use it with our eslint config.

## usage:
Add the following to your `package.json`:
```
...
"prettier": "@saulx/prettier-config",
"eslintConfig": {
  "extends": "@saulx/eslint-config"
},
"devDependencies": {
  "eslint": "^6.5.1",
  "prettier": "^1.18.2",
  "@saulx/eslint-config": "https://github.com/atelier-saulx/eslint-config",
  "@saulx/prettier-config": "https://github.com/atelier-saulx/prettier-config"
}
...
```
And run `yarn` or `npm i`
