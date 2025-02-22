# MongoDB $inc Operator Error with String Value

This example demonstrates an error in using the `$inc` operator in a MongoDB update query. The `$inc` operator is designed to increment numeric values, and using a string value will lead to unexpected results or an error. The solution shows the correct usage of the `$inc` operator.

## Bug
The bug involves using a string value ('1') with the `$inc` operator.  MongoDB expects a number to increment. 