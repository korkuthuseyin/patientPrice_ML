# Insurance Price Estimation Project

This project is designed to address the needs of an insurance company by utilizing machine learning to estimate prices for new patient entries based on existing data. The project involves a dataset stored in `insurance.csv` and a Jupyter Notebook `patientPrice.ipynb` that implements the machine learning workflow.

## Project Overview

The primary goal of this project is to use patient data to train a machine learning model that can accurately estimate the insurance cost for new patients. The model is built using the `scikit-learn` library, leveraging various features from the dataset to make predictions.

## Files Included

- **insurance.csv**: This file contains the patient information used for training the machine learning model. It includes features such as age, sex, BMI, children, smoker status, region, and charges.

- **patientPrice.ipynb**: This Jupyter Notebook file contains the entire workflow, from data exploration and preprocessing to model training, evaluation, and predictions for new entries. It provides a step-by-step guide to how the machine learning model is built and used.

## Key Features

- **Data Exploration and Visualization**: The project starts with an exploration of the `insurance.csv` dataset, including visualizations to understand the distribution of features and their relationships with the insurance charges.

- **Data Preprocessing**: The notebook demonstrates how to clean and preprocess the data, including encoding categorical variables, handling missing values, and feature scaling.

- **Model Training**: Various machine learning algorithms from `scikit-learn` are tested, and the best-performing model is selected based on evaluation metrics.

- **Prediction**: The trained model is used to predict insurance costs for new patient entries, demonstrating the practical application of the model.

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/korkuthuseyin/patientPrice_ML.git
