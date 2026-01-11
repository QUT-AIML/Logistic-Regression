# Logistic Regression

This repository is a comprehensive introduction to Logistic regression, designed to help users understand one of the foundational algorithms in machine learning through practical examples and real-world applications.

Unlike linear regression, which predicts a continuous number (like house prices), logistic regression predicts a **probability** between 0 and 1. To ensure the output stays within this range, it uses a specific mathematical function called the **Sigmoid (or Logistic) Function**.

## Projects Overview

This repository contains 4 different logistic regression projects:

#### 1. Asteroid Hazard Predictor
- **Data**: Dataset CSV file in `Data/nasa.csv`
- **Notebook**: `Asteriod Hazard Predictor/AsteroidHazardPredictor.ipynb`
- **Content**: Data retrieved from the NASA Near Earth Object (NEO) API. This API provides critical information about space objects—such as comets and asteroids—that pass close to our planet's orbit.
- **Objective**: The project’s primary objective is to classify whether an asteroid poses a threat to Earth based on data retrieved from the NASA Near Earth Object (NEO).
- **Status**: Ready for analysis

#### 2. Bank Loan Approval
- **Data**:  Dataset CSV file `Bank Loan Approval/data/dataset.csv`
- **Notebook**: `Bank Loan Approval/predict-bank-personal-loan.ipynb`
- **Content**: The dataset consists of 5,000 observations representing bank customers, featuring a mix of demographic data, relationship details with the bank, and their response to previous personal loan campaigns.
- **Objective**: The goal of this project is to build a predictive model using Logistic Regression to identify the underlying patterns that distinguish loan acceptors from non-acceptors
- **Status**: Ready for analysis

#### 3. Fake News Detection
- **Data**: Datasets on Fake and True news articles, CSV format located `/data`
- **Notebook**: `Fake News Detection/fake-news-classification.ipynb`
- **Content**: News Articles scraped from Web with Title, Text, Subject and Date columns
- **Objective**: Simple but effective text classification model to detect fake news articles.
- **Status**: Ready for analysis

#### 4. Heart Disease Prediction
- **Data**: Framingham Heart Study dataset `data/framingham.csv`
- **Notebook**: `Heart Disease Prediction/Predictive Modeling for 10-Year Cardiovascular Risk.ipynb`
- **Content**: The dataset consists of 4,238 records and 15 independent variables.
- **Objective**: This project implements a Logistic Regression classification model to predict the 10-year risk of future coronary heart disease (CHD) in patients
- **Status**: Ready for analysis


## Getting Started

1. Clone this repository
2. Install required Python packages for linear regression,  note that each Notebook contains cell to install the dependencies, if required:   
3. Choose a project folder and open the corresponding Jupyter notebook or in Google Collab
4. Follow the analysis and experiment with different regression techniques

## Project Structure

```
Logistic-Regression/
├── README.md
├── Asteriod Hazard Predictor/
│   ├── AsteroidHazardPredictor.ipynb
│   └── Data/
│	├── nasa.csv
├── Bank Loan Approval/
│   ├── predict-bank-personal-loan.ipynb
│   └── data/
│	├── dataset.csv
├── Fake News Detection/
│   ├── fake-news-classification.ipynb
│   └── Data/
│	├── Fake.csv
│	├── True.csv 
├── Pokémon/
│   ├── Pokémon Identification.ipynb
│   └── Data/
│	├── Pokemon.csv
└── Heart Disease Prediction/
    ├── Predictive Modeling for 10-Year Cardiovascular Risk.ipynb
    └── Data/
│	├── framingham.csv    
```

## Tips for Success

1. **Data Exploration**: Understand your data through visualization
2. **Feature Engineering**: Create meaningful features from raw data
3. **Assumptions Check**: Validate linear regression assumptions
4. **Regularization**: Use when dealing with overfitting
5. **Cross-Validation**: Evaluate model performance properly
6. **Interpretation**: Focus on understanding coefficient meanings
