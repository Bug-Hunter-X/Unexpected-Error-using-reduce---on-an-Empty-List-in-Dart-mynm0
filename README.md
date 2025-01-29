# Dart reduce() Error with Empty List

This repository demonstrates a common error encountered when using the `reduce()` method in Dart with an empty list. The `reduce()` method requires at least one element in the list; otherwise, it throws an error.

The `bug.dart` file shows the error, while `bugSolution.dart` provides a solution to handle this scenario gracefully.

## How to reproduce the bug
1. Clone this repository.
2. Run `bug.dart`.
3. Observe the error message.

## Solution
The solution involves checking if the list is empty before using `reduce()`.  See `bugSolution.dart` for the corrected code.