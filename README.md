# JavaScript Function Bug: Handling Undefined Arguments

This repository demonstrates a common JavaScript bug related to handling undefined function arguments.  The `foo` function correctly handles `null` values but fails to gracefully manage cases where arguments are `undefined`.

The `bug.js` file contains the buggy code, while `bugSolution.js` provides a corrected version. The solution addresses the issue by explicitly checking for both `null` and `undefined` using loose comparison (==) and strict equality (===).