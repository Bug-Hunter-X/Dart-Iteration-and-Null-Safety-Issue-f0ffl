# Dart Iteration and Null Safety

This repository demonstrates a potential issue when iterating over a list of objects in Dart and attempting to access object properties within the loop.  The problem arises when an element in the list might be null, causing a runtime error.  The provided examples show how this error can occur, and how to avoid it with proper null checks.

## Setup

This project requires Dart to be installed on your system. You can run the code using the Dart VM directly or through an IDE like IntelliJ or VS Code.

## How to run the code

1. Clone the repository.
2. Navigate to the project directory.
3. Run the `bug.dart` file using the command `dart bug.dart`. This should reproduce the potential issue.
4. Run `bugSolution.dart` which shows how to resolve the issue. 

## Issue and Solution Explained in the Files:

The `bug.dart` file contains code that iterates through a list of objects, showing how a null object could lead to an error.  The `bugSolution.dart` file demonstrates a robust approach to handle this by safely checking for null objects before accessing their properties.
