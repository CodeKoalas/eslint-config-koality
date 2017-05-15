# eslint-config-koality

#### A "Koality" ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) from your friends at [Code Koalas](https://codekoalas.com)

## Install

```bash
npm install --save-dev eslint-config-koality
```

The `ESLint Shareable Config` depends on [ESLint](http://eslint.org/) so you'll need to install ESLint as well (if you have not already installed it):

```bash
npm install --save-dev eslint
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

To use the JavaScript Standard Style shareable config, first run this:

```bash
npm install --save-dev eslint-config-koality
```

Then, add this to your .eslintrc file:

```
{
  "extends": "koality"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.

## License

MIT. License (c) [Code Koalas](https://codekoalas.com)
