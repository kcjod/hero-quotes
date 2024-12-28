# Hero Quotes

> Read a motivational quote, become better.

## Overview

The `hero-quotes` npm package provides a simple way to generate random motivational quotes. It helps you stay inspired and motivated with just one function call.

## Installation

To install the package, run the following command in your project:

```bash
npm install hero-quotes
```

## Usage

Once installed, you can import and use the `getquote` function to get a random quote.

```javascript
const { getquote } = require('hero-quotes');

console.log(getquote());
```

This will log a random motivational quote from a collection of 145 quotes.

## API

### `getquote()`

Returns a random motivational quote from a predefined list.

#### Example:

```javascript
const quote = getquote();
console.log(quote); // Outputs a random quote
```

## License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## Bugs and Issues

If you encounter any bugs or issues, please feel free to report them on the [GitHub Issues page](https://github.com/kcjod/hero-quotes/issues).

## Author

- **Krishna Chaitanya**  
  [GitHub Profile](https://github.com/kcjod)

## Repository

- [GitHub Repository](https://github.com/kcjod/hero-quotes)
```