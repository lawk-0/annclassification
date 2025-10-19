# ANN Classification (Churn Prediction)

This repository contains code, data and trained models for an Artificial Neural Network (ANN) project that predicts customer churn.

## Repository structure

- [.gitattributes](.gitattributes)
- [app.py](app.py) — minimal web/app entry point for serving the model (see file for details).
- [Churn_Modelling.csv](Churn_Modelling.csv) — dataset used for training/evaluation.
- [experiments.ipynb](experiments.ipynb) — exploratory analysis and experiments.
- [hyperparametertuningann.ipynb](hyperparametertuningann.ipynb) — hyperparameter tuning experiments.
- [model.h5](model.h5) — trained Keras/TensorFlow model used for inference.
- [prediction.ipynb](prediction.ipynb) — example notebook showing how to load `model.h5` and run predictions.
- [salaryregression.ipynb](salaryregression.ipynb) — separate regression example (included for reference).
- [requirements.txt](requirements.txt) — Python dependencies.
- [LSTM_RNN/](LSTM_RNN/) — related RNN/LSTM experiments (separate folder).

## Quick start

1. Create a virtual environment and install dependencies:

2. Run the app (example):
Open the URL printed by app.py (see app.py for how the app serves the model).

3. Notebooks
Open the notebooks in Jupyter / VS Code to reproduce experiments:
experiments.ipynb
hyperparametertuningann.ipynb
prediction.ipynb
salaryregression.ipynb
Model and data
Trained model: model.h5. Load with Keras/TensorFlow (see prediction.ipynb).
Raw dataset: Churn_Modelling.csv.
Notes
Inspect app.py to see how the model is loaded and served.
Use requirements.txt to reproduce the environment.
```sh
python -m venv .venv
source .venv/bin/activate   # on Windows: .venv\Scripts\activate
pip install -r requirements.txt
```
