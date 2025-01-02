# Unexpected NaN Result from Addition with Null in JavaScript

This repository demonstrates an uncommon JavaScript bug related to unexpected NaN (Not a Number) results when performing addition with null values.

## Bug Description
The `foo` function performs addition of two numbers. However, when `null` is passed as an argument, the addition results in `NaN`, which propagates to the `bar` function and causes unexpected behavior.

## Bug Reproduction
1. Clone this repository.
2. Open `bug.js`.
3. Run the code using Node.js (or a similar JavaScript environment).
4. Observe that the output includes `NaN` when null is passed to the `bar` function.

## Solution
The `bugSolution.js` file demonstrates how to resolve the issue by explicitly checking for and handling null values before performing the addition.

## Additional Notes
This bug highlights the importance of handling null or undefined values properly when performing arithmetic operations in JavaScript to prevent unexpected `NaN` results and to improve code robustness.