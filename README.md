# House_price_prediction
predicting house prie using linear regression , ridge regression and lasso based on classsification metrics Mean absolute error (MAE), Mean squared error(MSE), Root mean squared error (RMSE), R2.

A regression project that predicts median house values using the California Housing dataset from scikit-learn.

## Overview

This project trains and compares multiple linear regression models to predict house prices, then uses the best-performing model to make predictions on new data — including live predictions from user input.

## Dataset

- **Source:** `sklearn.datasets.fetch_california_housing`
- Features include median income, house age, average rooms, average bedrooms, population, average occupancy, latitude, and longitude
- Target: median house value (in $100,000s)

## Approach

1. **Data exploration** — checked shape, info, summary statistics, missing values, and duplicates
2. **Preprocessing** — train/test split, feature scaling with `StandardScaler`
3. **Model comparison** — trained and evaluated three models inside scikit-learn pipelines:
   - Linear Regression
   - Ridge Regression
   - Lasso Regression
4. **Model selection** — compared models using MAE, MSE, RMSE, and R², and selected the best model based on lowest RMSE
5. **Prediction** — used the best model to predict prices for new house data, including an interactive input mode where a user can enter feature values directly

## Tech Stack

- Python
- pandas
- scikit-learn (models, pipelines, preprocessing, metrics)
- NumPy

## How to Run

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `Houseprice_prediction.ipynb` in Jupyter Notebook or VS Code and run all cells

## Results

Model performance was compared using MAE, MSE, RMSE, and R² on the test set, with the lowest-RMSE model selected as the final predictor.

## Author

G. V. Mahidhar Reddy
[GitHub](https://github.com/mahidhar-ui) · [LinkedIn](https://linkedin.com/in/g-v-mahidhar-reddy-81)
