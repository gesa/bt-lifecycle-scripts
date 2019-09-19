**ALPHA** this package is not released yet, installation instructions will not work.

# Braintree Lifecycle Scripts

A collection of lifecycle scripts to be added to the `scripts: {}` object in one's package.json.

To use, first add to your package with `npm i @braintree/lifecycle-scripts`.

Next, add to the scripts object of your package.json:

```json
{
    "scripts": {
      "version": "run-version",
      "prepublishOnly": "run-publish"
    }
}
```
