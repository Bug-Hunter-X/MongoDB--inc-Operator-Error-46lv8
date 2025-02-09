# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The `$inc` operator is used to increment a numerical field by a specified value.  However, providing a non-numeric value results in an error or unexpected behavior.

## Bug Report
The bug occurs when attempting to increment a field with a non-numeric value.  The code in `bug.js` attempts to increment the `field` by the string `'abc'`, which is incorrect.

## Solution
The `bugSolution.js` file provides the correct usage, ensuring that the value passed to `$inc` is a number.