# CS 4375 – Assignment 1  
Linear Regression using Gradient Descent

## Overview

This project contains two implementations of linear regression on the UCI Student Performance dataset (id 320):

- **Part 1:** Manual implementation of gradient descent using NumPy  
- **Part 2:** Scikit-Learn implementation using `SGDRegressor`  

Both parts:
- Use the same dataset  
- Perform preprocessing and an 80/20 train-test split  
- Tune hyperparameters  
- Log results to CSV files  
- Report evaluation metrics (MSE, RMSE, MAE, R², Explained Variance)  
- Generate visualizations  

---

## Required Python Version

Python 3.9 or higher

---

## Required Packages

Install all required packages using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn ucimlrepo
```
Can run both files as python scripts using
```bash
python part1.py
python part2.py
```

part1.py will generate gd_trials_log.csv
part2.py will generate sgd_trials_log.csv





