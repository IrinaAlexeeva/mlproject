# Student performance prediction and deployment
This is an end to end ML project. 

## Problem statement
This project understands how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education. The scope is to create a production level code train and deploy.

## Data
Dataset Source - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
The data consists of 8 column and 1000 rows.

## Model
Regression model

## Deployments
1. Create Prediction Pipeline Using Flask Web APP
   - Github Workflow
   - app.py

2. Elastic Beanstalk in AWS
   - .ebextensions -> python.config
   - application.py
   - Elastic Beanstalk AWS
  
![Beanstalk](https://github.com/IrinaAlexeeva/mlproject/assets/144224513/1f1f560b-e786-4430-9a28-fe97c9a10b42)

3. ECR and EC2 in AWS
   - Docker Build
   - .github\workflow -> main.yaml
   - IAM User in AWS
   - ECR repository
   - EC2 virtual server
   - secret keys 




