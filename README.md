# 📊 Mean-Variance-Standard Deviation Calculator

This project calculates the **mean**, **variance**, **standard deviation**, **min**, **max**, and **sum** of a 3×3 matrix using **NumPy**.

It is a part of the freeCodeCamp Data Analysis with Python Certification.

## 📁 Files

- `mean_var_std.py` - Contains the `calculate()` function
- `main.py` - Runs and tests the function
- `test_module.py` - Unit tests

## 🧮 Function Overview

The `calculate()` function takes a list of 9 numbers, reshapes it into a 3x3 matrix, and returns a dictionary like this:

```python
{
  'mean': [[...], [...], ...],
  'variance': [[...], [...], ...],
  'standard deviation': [[...], [...], ...],
  'max': [[...], [...], ...],
  'min': [[...], [...], ...],
  'sum': [[...], [...], ...]
}
```

## 🚀 How to Run

```bash
python3 main.py
```

## ✅ How to Test

```bash
python3 -m unittest test_module.py
```
