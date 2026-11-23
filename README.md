
# PLP Python Week 6 Assignment

## Safe Functions

This assignment practices error handling using try and except.

### Files

- safe_tools.py: Contains three safe functions for division, number conversion, and dictionary lookup.
- README.md: Provides the assignment description and explains error handling.

### Why can the if check not catch abc on its own?

An if check can test whether input meets certain conditions, but it does not automatically catch errors that occur during conversion. When Python tries to convert "abc" into an integer using int(), it raises a ValueError. The try and except blocks catch this error and prevent the program from crashing.

