# tslint-config-uxpin

UXPin recommended TSLint configuration.

## Installation

Install TSLint and `tslint-config-uxpin`:

	yarn add --dev tslint tslint-config-uxpin
	
or

	npm install tslint tslint-config-uxpin --save-dev
	
Then create a `tslint.json` file in the root directory of your package, with the following contents:

```json
{
  "extends": "tslint-config-uxpin"
}
```

## Customization

In some cases, default configuration of the `tslint-config-uxpin` may not fit specifics of your projects. In most cases it's unrecommended but still possible to override the default configuration:

```json
{
  "extends": "tslint-config-uxpin",
  "rules": {
    "no-default-export": false,
    "match-default-export-name": true
  }
}
```
