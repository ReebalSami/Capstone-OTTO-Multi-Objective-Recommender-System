# Capstone Project

## Multi Objective Recommender System
### OTTO's Challenge on Kaggel
<br>
The goal of this project is to predict e-commerce clicks, cart additions, and orders through building a multi-objective recommender system based on previous events in a user session.

<br>

This challenge  will help improve the shopping experience for everyone involved. Customers will receive more tailored recommendations while online retailers may increase their sales

<br>


# ds-modeling-pipeline

Here you find a Skeleton project for building a simple model in a python script or notebook and log the results on MLFlow.

There are two ways to do it: 
* In Jupyter Notebooks:
    We train a simple model in the [jupyter notebook](notebooks/EDA-and-modeling.ipynb), where we select only some features and do minimal cleaning. The hyperparameters of feature engineering and modeling will be logged with MLflow

* With Python scripts:
    The [main script](modeling/train.py) will go through exactly the same process as the jupyter notebook and also log the hyperparameters with MLflow

Data used is the [OTTO's Challenge on Kaggel](https://www.kaggle.com/competitions/otto-recommender-system/data).

## Requirements:

- pyenv with Python: 3.9.8

### Setup

Use the requirements file in this repo to create a new environment.

```BASH
make setup

#or

pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

The `requirements.txt` file contains the libraries needed for deployment.. of model or dashboard .. thus no jupyter or other libs used during development.

# challenges and features to implement in the future

<br>

<br>

___
