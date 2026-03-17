Overview

This project builds a regression model to predict house prices using the California Housing dataset. The workflow includes data loading, preprocessing, exploratory data analysis, model training, and evaluation using standard regression metrics.

The goal of this project is to demonstrate a complete end-to-end machine learning pipeline using real-world data.

Dataset

The dataset used in this project is the California Housing dataset, provided by scikit-learn.

It contains the following features:

MedInc: Median income

HouseAge: Median house age

AveRooms: Average number of rooms

AveBedrms: Average number of bedrooms

Population: Block population

AveOccup: Average occupancy

Latitude

Longitude

Target variable:

Price: Median house value

Project Workflow

1. Data Loading

Loaded dataset using sklearn.datasets.fetch_california_housing

Converted data into a pandas DataFrame

Added target variable (price) to the dataset


2. Data Exploration

Checked dataset shape and structure

Verified missing values

Generated statistical summary using describe()

3. Feature Analysis

Computed correlation matrix

Visualized correlations using a heatmap (Seaborn)


4. Data Preparation

Split features and target into X and Y

Performed train-test split (80% training, 20% testing)


5. Model Training

Used XGBoost Regressor (XGBRegressor)

Trained model on training dataset


6. Model Evaluation

Evaluation metrics used:

R² Score

Mean Absolute Error (MAE)

Evaluation performed on:

Training data

Test data


7. Visualization

Scatter plot of actual vs predicted prices

Helps visualize model performance and prediction accuracy


Technologies Used

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

XGBoost


Results

The model demonstrates strong predictive performance using XGBoost

R² score and MAE are used to quantify accuracy

Visualization shows alignment between predicted and actual values


How to Run

Clone the repository

Install dependencies:
pip install numpy pandas matplotlib seaborn scikit-learn xgboost

Run the Jupyter Notebook:
jupyter notebook housepricepredictionbycj.ipynb

