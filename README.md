# MLOps pipeline - House Pricing

Welcome! This is a repository for a MLOps project with Kedro and MLflow!  
Goal of this project is to create a complete MLOps pipeline to predict house pricing.

## Overview
The [House Pricing dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data) from Kaggle is utilized for the purpose of creating and evaluating pipelines. Various pipelines were developed for different tasks, which can be found in the pipeline_registry.py file.

The project covers following aspects of MLOps:
- Experimentation and model versioning
- Data and concept drift evaluation
- Data quality tests
- Unit function tests

## Frameworks
In this repository following key frameworks and libraries were used:
   - [Kedro](https://docs.kedro.org/en/stable/)
   - [MLflow](https://mlflow.org/docs/latest/index.html)
   - [Kedro-MLflow](https://kedro-mlflow.readthedocs.io/en/stable/)
   - [NannyML](https://nannyml.readthedocs.io/en/stable/)
   - [Great Expectations](https://docs.greatexpectations.io/docs/)

## How to configure the local environment
 ```
python3 -m venv .mlops-env
source .mlops-env/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
 ```


