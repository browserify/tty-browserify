# tty-browserify

Browser stubs for the Node.js `require('tty')` module.

Browserify uses this module when you do `require('tty')` in a bundle. You should normally not use it directly.

## API

### `tty.isatty()`

Returns false.

### `new tty.ReadStream()`

Throws an error.

### `new tty.WriteStream()`

Throws an error.

## License

[MIT](./LICENSE)
