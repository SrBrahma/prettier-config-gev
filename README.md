# Installation

```shell
pnpm i -D prettier-config-gev prettier
# or
npm i -D prettier-config-gev prettier
# or
yarn add -D prettier-config-gev prettier
```

Add `"prettier": "prettier-config-gev"` to the root of your `package.json` if you don't intend to customize the Prettier. There isn't much to customize. Else, create a `.prettierrc.js` with the following:

```js
module.exports = {
  ...require("prettier-config-gev"),
  // Other rules
};
```
