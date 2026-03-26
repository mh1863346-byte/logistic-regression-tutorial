# Regularisation Paths in Logistic Regression
### Watching Features Disappear

A machine learning tutorial exploring how L1 (Lasso) and L2 (Ridge) regularisation affect logistic regression coefficients, using coefficient path visualisations on the Credit Card Default dataset.

## Learning Objectives
1. Explain what L1 and L2 regularisation do to model coefficients
2. Interpret a coefficient path plot and identify which features survive strong regularisation
3. Understand why L1 produces sparsity but L2 does not (the geometry argument)
4. Choose an appropriate regularisation strength using cross-validation

## Repository Structure
```
logistic-regression-regularisation-paths/
├── README.md
├── LICENSE (MIT)
├── requirements.txt
├── notebook/   → Jupyter tutorial notebook
├── figures/    → Generated visualisations
├── data/       → Dataset source notes
├── tutorial/   → Written tutorial report
└── references/ → Bibliography
```

## Quick Start
```bash
pip install -r requirements.txt
cd notebook/
jupyter notebook logistic_regression_regularisation_paths_tutorial.ipynb
```

## Author
Muhammad Huzaifa | University of Hertfordshire | March 2026
