# Deploying-machine-learning-models
Step by step process from end to end machine learning model deployment to production

# Different sections for deployment of ML model
## 1. Machine Learning - Research Environment
- Data gathering
- Feature engineering
- Feature selection
- Machine learning model building
- Model assessment
-- Both introduction and practical examples
-- Starting point for deploying your machine learning models

## 2. Machine Learning - System Architecture
- What is it and why it is important
- Challenges of creating a suitable system architecture
- Different architecture approaches
- Architecture components
-- Building Reproducible Machine Learning pipelines

## 3. Building a reproducible ML pipeline
-- How to transform your jupyter notebooks into production ready code
- Different ways utilised in the industry
- Procedural programming
- OOP with a custome pipeline
- OOP with third party pipeline
- Pros and cons of each method
- Our recommendation
- *Bonus : should we integrate feature selection into the production pipeline ?

## 4. Course setup and Key Tools
- Git refresher
- System path and python path refresher
- Virtual environments
- How to use the course resourses

## 5.Machine Learning Pipeline Application
- Train themodel and make predictions
- Ensuring data format - data validation
- Versioning and logging
- Building a python package with the model

## 6. Serving the Model via REST API
- Introduction to Flask
- Creating the API skeleton
- Versioning and logging
- Schema validation

## 7. Continuous Integration and Deployment Pipelines
- Introduction to CI/CD
- CircleCI
- Publishing the model to Gemfury
- Testing the CI pipeline

## 8. Differential Testing
- Setting up differential tests
- Differential testing in CI

## 9. Deploying to a PaaS (Heroku)
- What is a PaaS ?
- Utilising Heroku
- Tetsing the deployment manually
- Deploying to Heroku using CI

## 10. Running Apps with Containers (Docker)
- Intro to container and Docker
- Installing docker
- Creating an API App Dockerfile
- Building and Running a Docker container
- Releasing to Heroku utilising Docker

## 11. Deploying o an IaaS (AWS)
- Intro to AWS
- Creating an AWS account
- Installing and Configuring the AWS CLI
- Elastic Container Registry
- Elastic Container Service
- Deploying to ECS using CI

## 12. Deploying with Big Data - Dep Learning
- Classify images with CNN
- Challenges of deploying models using big data
- Updating applications to big data
- AWS S3 for large datasets

## 13. Common Issues Found During Deployment
- Summary of problems encountered during model deployment and how to resolve them


# Knowledge Requirement
## 1. Machine Learning
- Feature Engineering
- Feature Selection
- Linear and Logistic regression
- Random Forest Trees
- Gradient Boosted Trees (xgb)
- Model Diagnostics : ROC-AUC, mse

## 2. Python Programming
- Python 3.6
- Numpy 
- Pandas
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

## 3. Data competition Websites
- For datasets : www.kaggle.com

## 4. Environments, git
- Python environments
- Git for version control
