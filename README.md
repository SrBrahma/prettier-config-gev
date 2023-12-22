# NEW: You should now use Biome! Also, check my other package to use with Biome & ESLint: https://github.com/SrBrahma/eslint-config-biome

# Installation

```shell

npm i -D prettier-config-gev prettier
# or
yarn add -D prettier-config-gev prettier
# or
pnpm i -D prettier-config-gev prettier
# or
bun i -d prettier-config-gev prettier
```

Add `"prettier": "prettier-config-gev"` to the root of your `package.json` if you don't intend to customize the Prettier. There isn't much to customize. Else, create a `.prettierrc.js` with the following:

```js
module.exports = {
  ...require("prettier-config-gev"),
  // Other rules
};
```
