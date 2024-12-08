# MongoDB $inc operator error
This repository demonstrates a common error when using the `$inc` operator in MongoDB.  The `$inc` operator is used to increment a numerical value in a document. However, if a string value is provided instead of a number, the operation will fail to produce the expected results, or may even throw an error.

## Bug
The `bug.js` file shows the incorrect usage of the `$inc` operator, passing a string instead of a number.

## Solution
The `bugSolution.js` file shows the corrected code where the value passed to the `$inc` operator is a number. This ensures the operation works correctly and increments the age field as intended.

This example highlights the importance of using the correct data types in MongoDB operations for accurate and reliable results.