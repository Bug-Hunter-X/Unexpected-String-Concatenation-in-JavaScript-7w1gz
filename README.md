# Unexpected String Concatenation in JavaScript

This repository demonstrates a common JavaScript bug related to type coercion and the unexpected concatenation of strings and numbers.

## Bug Description
JavaScript's dynamic typing system can sometimes lead to unexpected behavior, especially when different data types are involved in arithmetic operations.  In the `bug.js` file, the `foo` function attempts to add two arguments, but because one is a string, JavaScript performs string concatenation instead of numerical addition. This can lead to logic errors in your application.

## Solution
The `bugSolution.js` file provides a solution where we explicitly convert the inputs to numbers using `parseInt` or `Number` before performing the addition. This ensures that the correct arithmetic operation is carried out.

## How to reproduce
1. Clone this repository.
2. Open `bug.js` and run the code in a JavaScript environment (like a browser's console or Node.js).
3. Observe the unexpected result.
4. Run `bugSolution.js` and see the corrected output.