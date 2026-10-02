# PLP Python Week 6 - Error Handling

- `safe_tools.py` - Contains safe functions that use try/except to handle common errors.
- `unbreakable.py` - Contains the additional error-handling practice for this assignment.

An `if` check cannot catch `abc` on its own because `abc` is text and the error happens when Python tries to convert it to an integer. The `int()` conversion raises a `ValueError`, which needs to be handled with `try` and `except`.