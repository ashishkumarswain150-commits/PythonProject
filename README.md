# Project PS-24: Class Marks Analyzer

## 📝 Problem Statement
Create a program that takes the marks of a class as a list, validates them and uses NumPy to calculate the mean, median, highest, lowest, standard deviation, pass count and the number of students above average.

- **Language:** Python 3
- **Concepts:** NumPy, Lists, Functions, Statistics
- **Note:** Marks are entered as numbers separated by spaces and must be from 0 to 100. Pass mark is 40. Standard deviation is the population value (`np.std` default).

## 🚀 Features
- Takes dynamic space-separated marks as input from the user.
- Validates the input (checks for numeric values and ensures marks are within the 0-100 range).
- Converts valid lists into `NumPy` arrays for fast mathematical operations.
- Calculates Mean, Median, Max, Min, and Population Standard Deviation.
- Analyzes and displays Passed students, Failed students, Pass Percentage, and Above-average students.

## 🛠️ Requirements
- Python 3.x
- NumPy library

To install NumPy (if not already installed), run:
```bash
pip install numpy
