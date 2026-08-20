
# COVID-19 Vaccination Prediction

Machine Learning project for analyzing and predicting daily COVID-19 vaccinations around the world.

## Project Steps

- Data loading and exploration
- Exploratory Data Analysis (EDA)
- Missing value analysis
- Data cleaning
- Feature engineering
- Time-based train/test split
- Linear Regression
- Random Forest Regression
- Model evaluation using MAE, RMSE and R²
- Actual vs Predicted comparison

## Features Used

- Country
- Month
- Day
- Day of week
- Previous day's vaccinations (lag_1)
- Vaccinations 7 days ago (lag_7)
- 7-day rolling average (rolling_7)

## Results

### Linear Regression

- MAE: 6863.94
- RMSE: 44624.86
- R²: 0.998869

### Random Forest

- MAE: 17787.28
- RMSE: 184606.89
- R²: 0.980637

Linear Regression achieved the best performance in this experiment.
