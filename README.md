# PLP Python Week 6 Assignment

## Safe Functions

This project demonstrates how to use `try` and `except` to handle common Python errors and keep a program running without crashing.

## Files

- `safe_tools.py` - Contains the three required functions and their test cases.
- `README.md` - Provides a brief description of the assignment and the error handling used.

## Functions

### `safe_divide(a, b)`

Divides `a` by `b`. If `b` is zero, it catches `ZeroDivisionError` and returns `Cannot divide by zero`.

### `safe_number(text)`

Converts text into an integer using `int()`. If the text is not a valid number, it catches `ValueError` and returns `Not a number`.

### `get_field(learner, key)`

Gets a value from a dictionary using the given key. If the key is missing, it catches `KeyError` and returns `Field not found`.

## Why can't an `if` check catch `abc` on its own?

An `if` statement can check a condition, but `int("abc")` raises a `ValueError`. The `try` and `except` block is needed to catch this error and prevent the program from crashing.

## Expected Output

5.0 Cannot divide by zero 42 Not a number 82 Field not found


## How to Run

Run the program using:

python safe_tools.py


## Author

**Amiir** 
GitHub: `thesonofbillionairemom-netizen`

