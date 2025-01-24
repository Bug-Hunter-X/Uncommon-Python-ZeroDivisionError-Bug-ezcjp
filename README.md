# Uncommon Python ZeroDivisionError Bug
This repository demonstrates a subtle ZeroDivisionError in a Python function. The error occurs when the function is called with a divisor of zero, which results in an exception.

## Bug Description
The `function` in `bug.py` attempts to divide `a` by `b`. If `b` is 0, this results in a `ZeroDivisionError`.  The error is not immediately obvious due to the context of the function call.

## Solution
The `bugSolution.py` file fixes this by adding a check for a zero divisor before performing the division. This prevents the exception from being raised.