# is-browser

  Test whether you're a component in browser or a package in npm

## Installation

  client:

    $ component install ForbesLindesay/is-browser

  server:

    $ npm install is-browser

## API

  This simply exports `true` or `false`:

```javascript
if (require('is-browser')) {
  console.log('The module was installed using component');
} else {
  console.log('The module was installed using npm');
}
```

## License

  MIT
