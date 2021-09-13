# @fvilers/is-string

A TypeScript type guard that validates if the given value is a string

## Installation

```
npm install @fvilers/is-string
```

or

```
yarn add @fvilers/is-string
```

## Usage

```ts
import isString from "@fvilers/is-string";

const variable: any = "This is a string";

if (isString(variable)) {
  // From here, variable is strongly typed as a string
  console.log("Variable is a string with length of", variable.length);
} else {
  console.log("Variable is not a string");
}
```

It will output:

```
Variable is a string with length of 16
```
