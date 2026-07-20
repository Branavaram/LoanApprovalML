# LoanApprovalML

![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-DataFrames-150458?logo=pandas&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

Machine learning notebooks for predicting loan approval, covering data preprocessing, classification, and regression modelling.

## Notebooks

1. **`01_data_preprocessing.ipynb`** — Data understanding and preprocessing for the classification task
2. **`02_classification_modelling.ipynb`** — Classification modelling and hyperparameter tuning
3. **`03_regression_modelling.ipynb`** — Regression modelling and ensemble learning

## Running it

These notebooks were developed in Google Colab and load data from Colab's `/content/` working directory. To run them elsewhere:

1. Upload the loan approval dataset CSV(s) referenced in the first cells of each notebook (the dataset itself isn't included in this repo).
2. Update the file paths from `/content/...` to wherever you've placed the data.
3. Run with a standard Python data-science stack: `pandas`, `numpy`, `scikit-learn`.

Notebook 2 and 3 depend on the cleaned output from Notebook 1, so run them in order.
