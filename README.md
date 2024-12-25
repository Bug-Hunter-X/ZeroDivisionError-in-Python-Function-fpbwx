# ZeroDivisionError in Python Function
This repository demonstrates a common error in Python: the ZeroDivisionError, which occurs when trying to divide a number by zero.  The `bug.py` file contains the erroneous code, while `bugSolution.py` provides a corrected version with error handling.

## Bug Description
The `function` attempts to divide `a` by `b`. If `b` is zero, a `ZeroDivisionError` is raised.

## Solution
The solution includes a check to prevent division by zero using a simple `if` condition.  Alternatively, more robust exception handling (using `try...except` blocks) can be implemented for production code.