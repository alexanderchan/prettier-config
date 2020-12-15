# About

Just a prettier config in case I forget these two settings and so version bumps are all that will be needed to update dependent proejcts.

```
{
  semi: false,
  singleQuote: true,
}
```

## Installation

Add to the package.json:

```json
 "prettier": "@alexnchan/prettier-config",
```

or 

```js
// .prettierrc.js
module.exports = {
  ...require("@alexmchan/prettier-config"),
  semi: false,
};
```

![Prettier Banner](https://raw.githubusercontent.com/prettier/prettier-logo/master/images/prettier-banner-light.png)
