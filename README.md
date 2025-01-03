# JavaScript Type Coercion Bug

This repository demonstrates a common, yet subtle, bug in JavaScript related to type coercion.  The `foo` function intends to add two numbers, but due to JavaScript's loose typing, it performs string concatenation when one of the inputs is a string.

## Bug Description
The bug lies in the `foo` function's lack of type checking.  When called with a number and a string, JavaScript implicitly converts the number to a string, resulting in unexpected behavior (concatenation instead of addition).

## How to Reproduce
1. Clone this repository.
2. Open `bug.js`.
3. Run the code in a JavaScript environment (e.g., Node.js, browser's console).
4. Observe the unexpected output.