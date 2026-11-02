# 📘 Assignment: Testing Python Functions with unittest

## 🎯 Objective

Learn to check Python functions automatically by writing tests with the built-in `unittest` framework. You will test expected results and edge cases, then run the test suite from the command line.

## 📝 Tasks

### 🛠️ Write Your First Unit Tests

#### Description
Create a module named `math_tools.py` with two small functions, then write a separate test module to check their behavior.

#### Requirements
Completed program should:

- Define `add_numbers(first, second)` in `math_tools.py` to return the sum of its two arguments.
- Define `is_even(number)` in `math_tools.py` to return `True` for even integers and `False` for odd integers.
- Create `test_math_tools.py` with a test class that inherits from `unittest.TestCase`.
- Include at least one test for each function using an appropriate `unittest` assertion.

### 🛠️ Check Edge Cases and Run the Test Suite

#### Description
Expand the tests to check less typical inputs, then run all tests with Python's test runner.

#### Requirements
Completed program should:

- Test `add_numbers()` with zero and with at least one negative number.
- Test `is_even()` with zero, a negative even integer, and an odd integer.
- Use descriptive test method names that start with `test_`.
- Run all tests with `python -m unittest` and confirm they pass.
