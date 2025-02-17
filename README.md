# Linear Regression Comparison

This project demonstrates the implementation of **Linear Regression** using two approaches:
1. **Manual implementation** using NumPy.
2. **Using Scikit-learn's `LinearRegression` model**.

## Features
- Computes regression coefficients (intercept and slope) manually.
- Uses Scikit-learn's built-in linear regression model.
- Calculates various error metrics for evaluation:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R-squared (R²)
- Compares and visualizes the results.

## Installation
To run this project, ensure you have Python installed along with the required dependencies:

```bash
pip install numpy matplotlib scikit-learn
```

## Usage
Run the Python script to compute and compare linear regression results:

```bash
python linear_regression_comparison.py
```

## Expected Output
The script will display regression coefficients and error metrics for both implementations and generate a comparison plot.

## Visualization
- **Blue scatter points:** Actual data.
- **Red line:** Regression line from the manual implementation.
- **Green dashed line:** Regression line from Scikit-learn.


---
**Author:** Luca Garcia

