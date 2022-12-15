# React useful stuff

## Plugins

### [babel-plugin-module-resolver](https://github.com/tleunen/babel-plugin-module-resolver)

This plugin can simplify the require/import paths in your project. For example:

```js
// Use this:
import MyUtilFn from 'utils/MyUtilFn';
// Instead of that:
import MyUtilFn from '../../../../utils/MyUtilFn';

// And it also work with require calls
// Use this:
const MyUtilFn = require('utils/MyUtilFn');
// Instead of that:
const MyUtilFn = require('../../../../utils/MyUtilFn');
```
