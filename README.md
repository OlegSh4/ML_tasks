# Classical Machine Learning Exercises

![Python](https://img.shields.io/badge/Python-3.10-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)

A collection of notebooks from my machine learning coursework, covering the fundamentals: EDA, linear and polynomial models, the bias–variance trade-off, classification metrics and neural networks.

## Contents

| Notebook | Topic | Data |
|---|---|---|
| `EDA.ipynb` | Titanic survival: exploratory analysis, missing values, encoding and logistic regression | `titanic.csv` |
| `Numeric.ipynb` | Air quality (AQI) analysis: distributions of numeric features and preprocessing | Beijing air quality (`PRSA_Data-2.csv`) |
| `Полиномиальные модели.ipynb` (*Polynomial models*) | Polynomial features for regression and classification, effect of polynomial degree | King County housing, synthetic data |
| `Недообучение и переобучение.ipynb` (*Underfitting & overfitting*) | Bias–variance trade-off, learning curves, precision / recall / F1 | Boston Housing, synthetic data |
| `MLP.ipynb` | Perceptron and multi-layer perceptron: decision boundaries vs. number of layers and neurons; Olivetti faces classification; regression evaluated with R² and MSE | synthetic blobs, Olivetti faces |

## Tech stack

Python · NumPy · pandas · scikit-learn · Matplotlib · Seaborn

## How to run

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

Each notebook is self-contained, and the datasets are included in the repository.
