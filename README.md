# YUIDoc Parch Theme

[![npm version](https://badge.fury.io/js/yuidoc-parch-theme.svg)](http://badge.fury.io/js/yuidoc-parch-theme)

An YUIDoc theme based on [yuidoc-ember-theme](https://github.com/offirgolan/yuidoc-ember-theme)

```bash
$ npm install yuidoc-parch-theme
```

### Configuration File

If your project uses a "yuidoc.json" file for configuration, add:

```javascript
"themedir" : "node_modules/yuidoc-parch-theme",
"helpers" : ["node_modules/yuidoc-parch-theme/helpers/helpers.js"]
```

Example:

```json
{
  "name": "Example",
  "url": "<GITHUB REPO URL>",
  "version": "0.1.0",
  "indexModule": "Welcome",
  "options": {
      "paths": "_location to parse_",
      "outdir": "docs",
      "exclude": "lib,docs",
      "themedir": "node_modules/yuidoc-parch-theme",
      "helpers": ["node_modules/yuidoc-parch-theme/helpers/helpers.js"]
  }
}
```
