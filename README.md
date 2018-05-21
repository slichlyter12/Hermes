# eslint-plugin-var-to-let

Convert `var` to `let` where applicable

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-var-to-let`:

```
$ npm install eslint-plugin-var-to-let --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-var-to-let` globally.

## Usage

Add `var-to-let` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "var-to-let"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "var-to-let/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





