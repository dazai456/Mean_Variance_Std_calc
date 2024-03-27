# Mean, Variance, and Standard Deviation Calculator

This project is part of the freeCodeCamp Data Analysis with Python certification. It involves creating a function that calculates statistical measures such as mean, variance, standard deviation, max, min, and sum across the rows, columns, and entire array of a 3x3 matrix.

## Project Objective

The goal is to write a Python function that can take in a list of nine numbers and output a dictionary containing the mean, variance, standard deviation, max, min, and sum for the rows, columns, and entire matrix.

## Functionality

The `calculate` function performs the following:

- Checks if the input list contains exactly nine numbers.
- Converts the list into a 3x3 Numpy array.
- Calculates the required statistical measures.
- Returns the results in a dictionary format.

## Usage

To use this function, simply import it into your Python script and pass a list of nine numbers to it:

```python
from mean_var_std import calculate

result = calculate([1, 2, 3, 4, 5, 6, 7, 8, 9])
print(result)