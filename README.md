# Investment Analytics & Machine Learning

A financial data analysis and machine learning project using technical indicators to analyze market trends and build models for classification and return prediction.

## Objectives

- Explore and analyze financial market data
- Study trends using technical indicators
- Engineer features from MACD behavior
- Develop a classification model for the `worked?` target
- Develop a regression model for `percentage_returns given`
- Compare different machine learning models

## Technical Indicators

The analysis uses the following features:

- Closing Price
- Volume
- EMA5
- EMA13
- EMA26
- MACD
- Signal
- RSI
- ROC

An engineered MACD-based feature is also developed to capture MACD crossover behavior and signal strength.

## Machine Learning Models

### Classification

The project evaluates:

- Random Forest Classifier
- Support Vector Classifier (RBF)

### Regression

The project evaluates:

- Random Forest Regressor
- Support Vector Regression (RBF)

## Workflow

1. Data exploration and understanding
2. Technical indicator analysis
3. Feature engineering
4. Feature scaling
5. Train/test split
6. Cross-validation
7. Model training
8. Classification and regression evaluation

## Evaluation Metrics

Classification is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Regression is evaluated using:

- R² score

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Repository Contents

- `Analysis.ipynb` — project analysis and machine learning workflow
- `Analysis.pdf` — exported project analysis/report

## Dataset

The original analysis notebook references a dataset named `XPREP8.csv`.

The dataset is not currently included in this repository, so the notebook cannot be reproduced end-to-end from this repository alone.

## Project Status

The analysis notebook and report have been organized into this repository as the project record. Reproducibility and evaluation improvements can be added as part of further development.
