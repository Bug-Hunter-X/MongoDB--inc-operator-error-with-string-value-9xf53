# MongoDB $inc Operator Error with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical field in a document. However, if a string value is provided instead of a number, the operation will fail.

## Bug
The `bug.js` file contains the incorrect code that uses the `$inc` operator with a string value. This will throw an error when executed.

## Solution
The `bugSolution.js` file provides the correct implementation where a numerical value is used with the `$inc` operator.