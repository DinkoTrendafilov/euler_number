# Euler's Number Approximation

This Python script approximates Euler's number (e) using Taylor series expansion.

## Mathematical Background

Euler's number can be expressed as the infinite series:

e = 1 + 1/1! + 1/2! + 1/3! + ... + 1/n! + ...


The more terms we calculate (higher n), the closer we get to the true value of e (≈ 2.718281828459045).

## Features

- Interactive input for number of iterations
- Displays progress after each iteration
- Formatted output with 15 decimal places
- Input validation
- Clean console output with separators

## Usage

1. Run the script:
   ```bash
   python euler_number_approximation.ipynb

    Enter the number of iterations when prompted.

Example output:

Enter the number of iterations: 10

----------------------------------------------------------------------
Iteration Progress:
Iteration     1: e ≈ 2.000000000000000
Iteration     2: e ≈ 2.500000000000000
...
Iteration    10: e ≈ 2.718281801146385
----------------------------------------------------------------------

Final approximation after 10 iterations:
e ≈ 2.718281801146385
----------------------------------------------------------------------

Requirements

    Python 3.x

    No external dependencies (uses built-in math module)

Notes

    With n=15, you'll get e accurate to 15 decimal places

    The script shows how quickly this series converges to the true value of e
