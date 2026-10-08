# Week 6 Assignment - Safe Functions

This assignment practices handling errors using try and except.

- `safe_tools.py` - Contains three safe functions for division, number conversion, and dictionary field lookup.
- `README.md` - Describes the assignment and explains why an if check cannot catch "abc" on its own.

An `if` check cannot catch `"abc"` when using `int()` because `"abc"` cannot be converted into an integer. Python raises a `ValueError`, so we use `try` and `except ValueError` to handle the error safely.