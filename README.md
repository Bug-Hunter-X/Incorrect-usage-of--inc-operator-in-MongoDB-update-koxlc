# Incorrect usage of $inc operator in MongoDB update
This example demonstrates an uncommon error related to the usage of the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical value in a document. Using a string value instead of a number will cause unexpected behavior or a failure in the update.

## Bug
The `bug.js` file showcases the erroneous usage of the `$inc` operator. The code attempts to increment the `field` by 'abc', which is a string and will result in an error.

## Solution
The `bugSolution.js` file corrects the issue. The code now correctly uses a numerical value to increment the `field`, providing the expected behavior.
