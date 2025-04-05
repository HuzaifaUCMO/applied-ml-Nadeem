# Lab 4 – Titanic Fare Regression

## Overview
This lab shifts from classification to **regression**:  
we predict the continuous variable **`fare`** (ticket price) in the Titanic dataset.  
We build four linear‑regression cases with different feature sets, then compare **Linear**, **Ridge**, **Elastic Net**, and a **Polynomial** model.  
A short bonus section repeats the workflow on the Iris dataset to earn extra credit.

## Folder Contents
| File / Folder | Purpose |
|---------------|---------|
| `ml04_huzaifanadeem.ipynb` | Fully‑executed Jupyter notebook with all analysis, plots, and reflections |
| `README.md`   | This file – explains what the lab does and how to run it |

## How to Run
1. Open the repository in VS Code (or JupyterLab).  
2. Launch `ml04_huzaifanadeem.ipynb`.  
3. Run cells from top to bottom; the notebook is self‑contained and will pull the dataset from `seaborn`.  
4. Review the summary table in Section 5 to see which model performed best.

## Key Steps Implemented
1. **Data cleaning & feature engineering**  
   * Imputed missing ages, created `family_size`, encoded `sex`/`embarked`.  
2. **Four linear‑regression cases** (`age`, `family_size`, `age+family_size`, `pclass+sex+family_size`).  
3. **Performance metrics** (R², RMSE, MAE) for train/test splits.  
4. **Regularized models** – Ridge and Elastic Net – to combat over‑fitting.  
5. **Polynomial regression** (degree 3) and visualization of cubic vs actual fares.  
6. **Bonus** – simple Ridge regression on the Iris dataset (predicting petal length).

## Results (quick snapshot)
* **Best feature set:** `pclass`, `sex`, `family_size` (Case 4).  
* **Best model:** Ridge Regression – highest Test R² and lowest error.  
* Polynomial fit captured curvature for extreme ages but over‑fit high‑fare outliers.

## Requirements
* Python 3.9+  
* `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit‑learn` (all imported at top of notebook).

## Author
Huzaifa Nadeem  
4-4-2025
