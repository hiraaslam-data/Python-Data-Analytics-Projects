# House Price Prediction (Regression)

A machine learning project that predicts house prices with Linear Regression, then compares it against Ridge and Lasso regularized models.

**Notebook:** `house_pricing.ipynb`
**Input:** `House Price Prediction Dataset.csv` (Kaggle)

## What this project does
1. Loads the dataset and previews it
2. Drops the `Id` column, fills missing numeric values with the median
3. One-hot encodes categorical features: `Location`, `Condition`, `Garage`
4. Plots a correlation heatmap and ranks features by correlation with `Price`
5. Splits the data 80% train / 20% test (`random_state=42`)
6. Trains a Linear Regression model
7. Evaluates it with MSE, RMSE and R² score
8. Visualizes results: Actual vs Predicted scatter plot and residual plot
9. Analyzes feature coefficients to see which features affect price most
10. Compares Linear, Ridge and Lasso regression in one summary table

## Tools & libraries
Python, pandas, NumPy, matplotlib, seaborn, scikit-learn

## How to run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook house_pricing.ipynb
```
Place `House Price Prediction Dataset.csv` in the same folder as the notebook.

## Skills shown
Feature encoding, correlation analysis, train/test split, regression modeling, model evaluation, residual analysis, regularization (Ridge/Lasso)
