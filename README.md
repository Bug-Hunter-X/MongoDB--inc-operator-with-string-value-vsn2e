# MongoDB $inc operator with string value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries.  The `$inc` operator is designed to increment a numeric field by a specified value.  However, if you attempt to use it with a string, it will lead to unexpected behavior or errors.

The `bug.js` file showcases the incorrect usage, while `bugSolution.js` provides the corrected implementation.
