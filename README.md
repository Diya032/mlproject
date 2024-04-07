# END TO END MACHINE LEARNING PROJECT: STUDENT PERFORMANCE PREDICTION

## Table of Contents

1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Problem Statement](#problem-statement)
4. [Dataset](#Dataset)
5. [Modular Code](#modular-code)
6. [Prediction Pipeline](#prediction-pipeline)
7. [Deployment](#deployment)
8. [Steps](#Steps)

---

## Introduction

This project aims to predict student performance based on various factors such as gender, ethnicity, parental level of education, lunch type, and test preparation course, along with math, reading, and writing scores.

---

## Project Structure

The project is structured as follows:

- **data**: Contains the dataset used for training and testing.
- **src**: Source code directory.
  - **exception.py**: Defines custom exceptions for error handling.
  - **logger.py**: Configures logging for the project.
  - **data_ingestion.py**: Handles data ingestion from CSV files.
  - **data_transformation.py**: Performs data transformation and preprocessing.
  - **model_trainer.py**: Trains machine learning models on the processed data.
  - **predict_pipeline.py**: Implements the prediction pipeline.
- **requirements.txt**: Lists all the dependencies required to run the project.
- **application.py**: Flask web application for hosting the prediction service.
- **home.html**: HTML template for the input form used in the web application.
- **README.md**: Documentation file providing an overview of the project.

---

## Problem Statement

The goal of the project is to predict student performance scores in math, reading, and writing based on demographic and educational background information. This involves exploratory data analysis (EDA), feature engineering, and model training.

---
## Dataset
- Dataset: 8 columns, 1000 rows
- Columns: 
    - gender(M/F)
    - race/ethnicity (Group A,B,C,D,E)
    - parental level of education (categorical)
    - Lunch (standard, free/reduced)
    - test prep course before test (complete/incomplete)
    - math score (numerical)
    - reading score (numerical)
    - writing score (numerical)

---

## Modular Code

The project follows a modular code structure to enhance maintainability and scalability. Each component, such as data ingestion, data transformation, and model training, is encapsulated within separate modules for easy management and testing.

---

## Prediction Pipeline

The prediction pipeline is implemented using Flask, a micro web framework for Python. Users can input their demographic and educational information through an HTML form, which is then processed by the prediction pipeline to generate performance predictions.

---

## Deployment

The project can be deployed using various cloud services such as AWS (Elastic Beanstalk or Docker) or Azure (GitHub Actions or MLOps). Detailed instructions for deployment are provided in the respective deployment guides.

---

## Steps

- Setting up of Github Repository
    - create new conda environment
    - setup.py
    - requirements.txt
    - .gitignore file

- Project structuring
    - pipelines
    - logging
    - Exception handling

- Problem Statement Understanding
    - EDA and Feature engineering
    - Model Training (Jupyter Notebooks)

- Modular Code it
    - Data Ingestion
    - Data Transformation
    - Model Trainer
    - utils.py 

- Hyper-Parameter Tuning

- Create Prediction Pipeline using Flask Web App
    - application.py (Flask)
    - home.html (Form in html: Input for prediction)
    - predict pipeline

- Deployment
    - Choices :  AWS [Elastic Beanstalk or Docker] OR Azure[Github actions or MLOPS]
