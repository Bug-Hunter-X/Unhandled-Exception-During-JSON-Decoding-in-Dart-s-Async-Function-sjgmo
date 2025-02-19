# Unhandled Exception During JSON Decoding in Dart

This repository demonstrates a common error in Dart's asynchronous programming: failing to handle exceptions during JSON decoding. The `bug.dart` file contains code that throws an unhandled exception when the JSON response is malformed. The `bugSolution.dart` file provides a robust solution with comprehensive exception handling.

## How to Reproduce

1. Clone this repository.
2. Run `bug.dart`.
3. Observe the unhandled exception.

## Solution

The `bugSolution.dart` file shows a solution with improved error handling. A `try-catch` block is used to catch potential exceptions during JSON decoding and provides a more robust solution to handling errors gracefully.