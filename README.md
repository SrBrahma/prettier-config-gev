# Installation

```shell
npm i -D prettier-config-gev prettier
# or
yarn add -D prettier-config-gev prettier
# or
pnpm i -D prettier-config-gev prettier
```

Create a `.prettierrc.js` with the following:

```js
module.exports = {
  ...require("prettier-config-gev"),
  // Other rules
};
```

It's also possible to add `"prettier": "prettier-config-gev"` to the `package.json` but that doesn't allow customization. But there aren't many to do in prettier.