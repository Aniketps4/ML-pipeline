# ML-pipeline
# Machine Learning Model Pipeline

This repository contains a Jupyter Notebook implementing a machine learning pipeline for structured data analysis. It is designed to dynamically load parameters from a JSON configuration file and process a dataset with customized preprocessing, feature engineering, and model training steps.

## Features

- Load configurable parameters from a JSON file (`algoparams_from_ui.json`)
- Perform preprocessing on numerical and categorical features
- Generate interaction and polynomial features
- Reduce dimensionality by selecting important features
- Use `scikit-learn` pipelines for modular design and reproducibility
- Support hyperparameter tuning with `GridSearchCV`

## Files

- `model.ipynb`: Main Jupyter Notebook containing the ML pipeline
- `algoparams_from_ui.json`: JSON file specifying parameters like feature types, model options, etc.
- `README.md`: This file

## Requirements

Install the required Python libraries with:

```bash
pip install -r requirements.txt
