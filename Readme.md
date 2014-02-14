
# util-inspect

This is an extraction of Node's `inspect` utility from the `util`
module, with two fundamental advantages:

- Single, focused module
- Compatible with all browsers and environments.

## How to use

With browserify or node:

```js
var inspect = require('util-inspect');
console.log(inspect({}));
```

## License

MIT – Copyright (c) 2010-2014 Joyent, Inc.
