# MLOps pipeline - House Pricing

Welcome! This is a repository for a MLOps project with Kedro and MLflow!

## Overview
- In this repository you find a complete ML pipeline created with the libraries listed below.
   - [Kedro](https://docs.kedro.org/en/stable/)
   - [MLflow](https://mlflow.org/docs/latest/index.html)
   - [Kedro-MLflow](https://kedro-mlflow.readthedocs.io/en/stable/)
- To create and test the pipelines the House Pricing dataset from kaggle is used (https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data).
- Several pipelines were created for different tasks, which can be found in pipeline_registry.py
- A requiremets.txt is provided to replicate the used packages.

## How to configure the local environment

 ```
python3 -m venv .mlops-env
source .mlops-env/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
 ```


