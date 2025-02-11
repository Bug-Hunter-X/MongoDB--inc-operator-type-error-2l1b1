# MongoDB $inc Operator Type Error
This example demonstrates an error that can occur when using the `$inc` operator in MongoDB's `updateOne` method. The error occurs when attempting to increment a numerical field with a non-numerical value (in this case, a string).

## Bug Description
The provided code attempts to increment the `age` field by '1' (a string), which results in a type error. The `$inc` operator requires a numerical value for the increment. 

## Solution
The solution is to provide the correct numerical value to the `$inc` operator.