# RecursionError in Factorial Function

This repository demonstrates a common error in Python related to recursion: the `RecursionError: maximum recursion depth exceeded` error.

The `factorial_error.py` file contains a recursive factorial function that does not handle negative input correctly, leading to infinite recursion.

The `factorial_solution.py` file provides a corrected version of the function that gracefully handles negative input and avoids the error.

The issue occurs because the recursive call `factorial(n-1)` continues indefinitely for negative values of `n`, leading to the stack overflow and `RecursionError`. The solution introduces a check for negative input, returning an appropriate value or raising an exception.