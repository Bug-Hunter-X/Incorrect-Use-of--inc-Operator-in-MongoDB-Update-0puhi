# Incorrect Use of $inc Operator in MongoDB Update
This example demonstrates a common error when using the `$inc` operator in MongoDB update queries. The `$inc` operator is used to increment or decrement a numerical field by a given value.  However, if a non-numeric value is provided, MongoDB will not throw an error but the update may not work as expected. This can be a difficult error to track down.

The bug showcases this error, and the solution shows the correct way to use the `$inc` operator.