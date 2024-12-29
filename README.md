# MongoDB $inc Operator with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries.  The `$inc` operator is designed to increment a numeric field, but using a string value instead can lead to unpredictable results. The issue is highlighted in `bug.js`, and the solution is provided in `bugSolution.js`.