# Unexpected Type Coercion in JavaScript
This example demonstrates a common JavaScript pitfall: unexpected type coercion during arithmetic operations.  When a number and a string are used together in an arithmetic expression, JavaScript implicitly converts the number to a string, resulting in string concatenation instead of numerical addition. This can lead to bugs that are difficult to track down.

## How to Reproduce
1. Clone this repository.
2. Run `node bug.js` to see the unexpected string concatenation.
3. Run `node bugSolution.js` to see the corrected behavior with explicit type checking.

## Solution
The solution involves explicitly converting the operands to numbers before performing the arithmetic operation, ensuring consistent behavior across different input types.