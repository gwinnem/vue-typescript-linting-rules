# vue-typescript-linting-rules
My favourite linting rules for a VUE 3 Typescript project.
## How to use the package
In your project, create an `.eslintrc.js` that includes at least the following configuration:
```ts
const { resolve } = require(`path`);
module.exports = {
  root: true,
  extends: [
    `vue-typescript-linting-rules`,
  ],
  parserOptions: {
    project: resolve(__dirname, './tsconfig.json'),
    tsconfigRootDir: __dirname,
  }
}
```
