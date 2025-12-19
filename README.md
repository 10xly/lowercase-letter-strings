# `lowercase-letter-strings`

A collection of lightweight, single-purpose NPM packages that export individual lowercase letter strings. This project follows the philosophy of extreme modularity, allowing you to bundle only the specific characters your application requires.

## Installation

Install the specific letter package you need via npm:

```bash
npm install @lowercase-letters/a
# or
npm install @lowercase-letters/z
```

## Usage

Each package exports the lowercase letter as the primary export via `module.exports`.

```javascript
const a = require('@lowercase-letters/a');
const b = require('@lowercase-letters/b');

console.log(a); // "a"
console.log(b); // "b"
```

## Package List

The project consists of 26 individual packages, one for each letter of the English alphabet:

* `@lowercase-letters/a`
* `@lowercase-letters/b`
* `@lowercase-letters/c`
* ... and so on through `@lowercase-letters/z`

## Folder Structure

In this GitHub repository, each package is located in its own directory named after the letter:
* `/packages/a`
* `/packages/b`
* `/packages/c`
* ...and so on.

## License

Unlicense