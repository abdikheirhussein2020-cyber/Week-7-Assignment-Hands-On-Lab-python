# Week 7 Python Assignment — Lists

## Overview

This assignment demonstrates how to work with Python lists. It covers accessing list items using indexes, adding and removing items, using loops, checking membership, counting items, and finding the longest item name.

## Files Included

### 1. `list_warmup.py`
Demonstrates basic list operations:
- Creates a list containing four fruits.
- Prints the first and last items using indexes.
- Uses `append()` to add a fruit.
- Uses `remove()` to remove a fruit.
- Uses `len()` to count the remaining fruits.

### 2. `shopping_list.py`
Implements an interactive shopping list manager:
- Starts with an empty list.
- Uses a `while` loop to display a menu.
- Allows users to add items using `append()`.
- Checks whether an item exists using `in` before removing it.
- Displays a helpful message when an item is not on the list.
- Uses a `for` loop to display items individually.
- Exits when the user selects `done`.

### 3. `list_report.py`
Generates a report from a predefined shopping list:
- Prints each item with a number.
- Counts item names containing more than four characters using a loop and an `if` statement.
- Finds the longest item name using a loop and length comparisons.

## Concepts Practiced

- Creating and modifying lists.
- Accessing list elements using indexes.
- Using `append()`, `remove()`, and `len()`.
- Using `while` and `for` loops.
- Applying `if` statements and the `in` operator.
- Counting items and comparing string lengths.
- Handling missing items without crashing the program.

## Expected Results

The shopping list manager should add and remove items correctly, display a warning when an item is missing, and exit with a goodbye message.

The list report should display all five items with numbers, report **3** item names with more than four characters, and identify **sweet potatoes** as the longest item name.

## How to Run the Programs

Run each program from the VS Code terminal using Python:

```bash
py list_warmup.py
py shopping_list.py
py list_report.py
```

## Screenshots

The following screenshots should be saved with the assignment files:

- `list_warmup_output.png` — output from Part A.
- `shopping_list_output.png` — output from Part B.
- `list_report_output.png` — output from Part C.

## Conclusion

This assignment improved my understanding of Python lists and how to manipulate and process list data using loops, conditions, built-in functions, and user input.