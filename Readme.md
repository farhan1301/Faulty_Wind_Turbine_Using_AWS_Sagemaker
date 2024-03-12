# Exploratory Data Analysis and Fault Detection in Wind Turbines with AWS SageMaker
This repository contains Jupyter notebooks and resources for conducting exploratory data analysis (EDA) of wind turbine data and detecting faulty states using XGBoost in AWS SageMaker.

## Description
The project is divided into two main parts:

- Exploratory Data Analysis (EDA): Analyzing wind turbine data to understand its composition and prepare it for modeling. This includes data loading, preprocessing, feature scaling, and visualization.

- Fault Detection with XGBoost: Building and training an XGBoost model to detect when a wind turbine is in a faulty state. This involves preprocessing steps, model training and tuning, and evaluation.

## Prerequisites
AWS account with access to SageMaker and S3.
Python 3.8+ environment with pip.

## Setup
S3 Bucket: Ensure your wind turbine data is stored in an S3 bucket. Update the BUCKET_NAME in the notebooks to point to your S3 bucket.

Install Libraries: Make sure to install all necessary libraries as described in the notebooks.

## EDA Overview
The EDA part involves understanding data dimensions, missing values, data types, and generating several visualizations to uncover patterns within the data.

## Modeling with XGBoost
The modeling part covers setting up an XGBoost model in SageMaker, including preprocessing data, setting hyperparameters, training the model, and evaluating its performance on test data.

## Evaluation Metrics
Model performance is evaluated using metrics such as AUC, accuracy, recall, and precision. Visualizations include feature importance and confusion matrices.
