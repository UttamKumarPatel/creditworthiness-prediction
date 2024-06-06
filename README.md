# Creditworthiness Prediction using Random Forest

This repository contains code and resources for predicting the creditworthiness of individuals based on various financial attributes using a Random Forest ensemble method. The project aims to classify individuals as good or bad credit risks, helping financial institutions make informed lending decisions.

## Project Overview

### Objectives
- **Predict Creditworthiness**: Classify individuals as either good or bad credit risks.
- **Utilize Random Forest**: Leverage the Random Forest ensemble method for robust and accurate predictions.
- **Preprocess Data**: Implement data preprocessing techniques to handle both numerical and categorical data.

### Dataset
The dataset used in this project is the German Credit Data, which includes various financial attributes of individuals along with their credit risk labels. The data consists of both numerical and categorical features.

### Features
- **Account Balance**: Numeric
- **Duration**: Numeric
- **Credit Amount**: Numeric
- **Purpose**: Categorical
- **Employment**: Categorical
- **Personal Status and Sex**: Categorical
- **Other attributes**: Various numerical and categorical features

### Target Variable
- **Credit Risk**:
  - `1`: Good Credit Risk
  - `2`: Bad Credit Risk

## Project Structure
- **data/**: Contains the dataset files.
- **notebooks/**: Jupyter notebooks for exploratory data analysis and model development.
- **src/**: Source code for data preprocessing, model training, and evaluation.
- **README.md**: Project overview and setup instructions.
