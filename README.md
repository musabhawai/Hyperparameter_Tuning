# Hyperparameter Tuning – GridSearchCV & RandomizedSearchCV

## 📌 Overview
This repository contains examples demonstrating *hyperparameter tuning* techniques using:
1. *GridSearchCV* – Exhaustive search over specified parameter values.
2. *RandomizedSearchCV* – Random search over parameter distributions for faster tuning.

## 📖 About Hyperparameter Tuning
Hyperparameter tuning is the process of *finding the best set of parameters* for a machine learning model to maximize performance.
- *GridSearchCV*: Tries all possible combinations of given parameters.
- *RandomizedSearchCV*: Tries a fixed number of random combinations, which is faster for large parameter spaces.

## 🛠 Technologies Used
- Python 
- Pandas
- NumPy
- Scikit-Learn

## 📂 Projects Included
### 1️⃣ GridSearchCV Example
- *Goal*: Improve model accuracy by testing multiple parameter combinations.
- *Process*:
  - Define parameter grid
  - Train model with all parameter combinations
  - Select the best parameters based on cross-validation results

### 2️⃣ RandomizedSearchCV Example
- *Goal*: Find optimal parameters quickly by searching randomly.
- *Process*:
  - Define parameter distributions
  - Train model with a limited number of random parameter samples
  - Select the best parameters based on cross-validation results
