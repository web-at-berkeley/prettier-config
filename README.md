# prettier-config

The default prettier configuration for all WDB projects.

Submodule within `mono`

## How To Use

Start by installing Prettier and this configuration into your app:

```bash
yarn add -D prettier @web-at-berkeley/prettier-config
```

Create a `.prettierrc.js` file (your prettier config file)

```bash
touch .prettierrc.js
```

Add the following:

```js
module.exports = {
  ...require('@web-at-berkeley/prettier-config'),
}
```

Make sure you install your IDE specific Prettier plugin (like [this one](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) for VSCode) and you're good to go!

If using yarn PnP, make sure you run `yarn sdks <your editor>`!
