### udacity-capstone
Capstone Project for Udacity AWS MLE Nanodegree
## Predicting Chronic Absenteeism
This is a project using AutoGluon to create a model to predict whether a student is likely to be chronically absent
## Project Set Up and Installation
Download the 2016 Parent and Family Involvement in Education survey data from the NHES at https://nces.ed.gov/nhes/data/2016/pfi/pfi_pu.csv and upload to S3.
If desired, user's guide and codebooks are available at https://nces.ed.gov/nhes/dataproducts.asp
In SageMaker Studio, open the Jupyter notebook with Python 3 (MXNet 1.8 Python 3.7 GPU Optimized) kernel and ml.t3.medium instance
Install the dependencies in the code
## Script Files Used
1. ag_model.py
2. tabular_serve.py
3. tabular_train.py
## Config Files Used
1. config.yaml
2. config-roc-auc.yaml

All script files and config files were adapted from AWS SageMaker examples: https://github.com/aws/amazon-sagemaker-examples/tree/master/advanced_functionality/autogluon-tabular-containers
