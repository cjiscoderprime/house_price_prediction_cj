# House Price Prediction

Machine learning model to predict California housing prices using XGBoost.

## What this project does

This project builds a regression model that predicts median house prices using real-world housing data. It demonstrates a complete machine learning pipeline from raw data to evaluated model.

## Dataset

California Housing dataset (from scikit-learn)

**Input features:**
- MedInc – Median income  
- HouseAge – Median house age  
- AveRooms – Average rooms  
- AveBedrms – Average bedrooms  
- Population  
- AveOccup – Average occupancy  
- Latitude  
- Longitude  

**Target:**
- Price – Median house value  

## Pipeline

### Data
- Loaded using `fetch_california_housing`
- Converted to pandas DataFrame
- Target column added

### Exploration
- Checked shape, structure, and null values  
- Used `describe()` for summary statistics  

### Feature Analysis
- Correlation matrix computed  
- Heatmap used to identify relationships  

### Preparation
- Split into features (X) and target (y)  
- Train-test split (80/20)  

### Model
- XGBoost Regressor (`XGBRegressor`)  
- Trained on structured tabular data  

### Evaluation
- R² Score  
- Mean Absolute Error (MAE)  
- Evaluated on both training and test sets  

### Visualization
- Actual vs Predicted scatter plot  
- Used to inspect model performance  

## Tech Stack

Python, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, XGBoost

## Results

The model achieves strong predictive performance on housing price estimation.  
Predictions closely align with actual values, indicating effective learning of feature relationships.

## How to Run

```bash
git clone <repo-link>
cd house-price-prediction
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
jupyter notebook housepricepredictionbycj.ipynb
```

  

## Author

Chandragupta Jejurkar  
Penn State York – Information Technology  
