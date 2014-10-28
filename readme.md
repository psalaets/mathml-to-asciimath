# mathml-to-asciimath

Convert subset of MathML to ASCIIMathML.

## Usage

```
var convert = require('mathml-to-asciimath');

var mathml = '<math><mn>1</mn><mo>+</mo><mn>2</mn></math>';
convert(mathml); // => '1 + 2'
```

## This module is not

- comprehensive
- performant

## Long term goal

Be the inverse of [ForbesLindesay/ascii-math](https://github.com/ForbesLindesay/ascii-math)

## License

MIT
