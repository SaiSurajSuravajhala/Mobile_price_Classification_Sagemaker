# Mobile-Prices-Classification-With-AWS-Sagemaker

## Overview
Implementation of a machine learning pipeline for mobile phone price classification using AWS SageMaker with Random Forest algorithm.

## Technical Implementation
1. **Environment Setup**
   - AWS IAM role configuration with SageMaker execution permissions
   - Data handling in Google Colab and VS Code environments

2. **Data Engineering**
   - Dataset preparation with mobile phone features
   - Train/test split (20% test data)
   - CSV handling across environments

3. **SageMaker Workflow**
   - SKLearn estimator with framework version 0.23-1
   - Hyperparameter configuration: 100 estimators
   - Spot instance utilization (66.3% cost savings)
   - Custom entry point script (script.py)

4. **Model Performance**
   - Accuracy: 85.75%
   - F1-scores: 0.96 (class 0), 0.80 (class 1), 0.75 (class 2), 0.91 (class 3)
   - Training time: 89 seconds

5. **Infrastructure**
   - ml.m5.large instance
   - S3 bucket integration
   - AWS session management

## Results
Successfully built and trained Random Forest classifier in SageMaker's managed environment, demonstrating end-to-end ML deployment on AWS infrastructure.
