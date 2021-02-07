# What does this module do?

This module finds the closest string match or matches in an array using livenshtein distance

# Installation

`npm i closest-word --save`

# Examples

```
const closest-word = require("closest-word");

//normal usage
console.log(closest-word("dag", ["dog", "pumpkin"])); //dog

//multiple values
console.log(closest-word("hello", ["jello", "yellow", "bello"], 2)); //["jello", "bello"]
```