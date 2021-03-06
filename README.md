# eslint-plugin-nova

ESLint rules for the [Nova extension API](https://docs.nova.app).

## Installation

You'll first need to install [ESLint](https://eslint.org/):

```
$ npm install eslint --save-dev
```

Next, install `eslint-plugin-nova`:

```
$ npm install eslint-plugin-nova --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-nova` globally.

## Usage

Add `nova` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "nova"
    ]
}
```

Finally, add `nova/nova` to the env section of your `.eslintrc` file:

```
"env": {
    "commonjs": true,
    "nova/nova": true
}
```
