# Lab 04 – Predicting Fare Using Regression

This project explores different ways to predict a continuous target: fare (the amount paid for a Titanic ticket). I used different features and tried multiple regression models to see which worked best.

## Folder: lab04

Notebook: `ml04_davidrm.ipynb`

## Notebook Structure
## The notebook is organized into the following sections:

1. **Import and Inspect Data** – Load Titanic dataset and check for missing values.
2. **Data Exploration and Preparation** – Clean the data and create new features.
3. **Feature Selection** – Try different feature combinations to predict fare.
4. **Train Models** – Train and evaluate Linear Regression models.
5. **Compare Models** – Try Ridge, Elastic Net, and Polynomial Regression.
6. **Final Thoughts** – Summarize findings and reflect on challenges.


## Goals

- Use Titanic data to predict fare
- Try different features like age, family size, and sex
- Train and compare models like:
  - Linear Regression
  - Ridge
  - Elastic Net
  - Polynomial Regression

## Key Findings

- The best model was Polynomial Regression (degree 3)
- age, family_size, and sex were the most helpful features
- Simple models underfit; regularization helped a bit
- Higher-degree models (like degree 7) started to overfit

##  Tools Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Create and activate a virtual environment:
**On macOS/Linux:**
```
python3 -m venv .venv
source .venv/bin/activate
```

**On Windows (PowerShell):**
```
python -m venv .venv
.venv\Scripts\Activate.ps1
```

## Install Required Packages
```
pip install pandas numpy scikit-learn matplotlib seaborn
```