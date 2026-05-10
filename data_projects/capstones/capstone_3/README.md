# NYC Taxi Trip Duration Analysis

## Overview

This project analyzes NYC Yellow Taxi trip data to identify key factors associated with trip duration and develop machine learning models capable of predicting travel time.

## Approach

- Data cleaning and preprocessing
- Feature engineering and scaling
- Exploratory Data Analysis (EDA)
- Model training (Linear Regression, Ridge Regression, Random Forest)
- Feature importance analysis
- Refined Random Forest modeling without fare-related variables

## Results

| Model | R² | RMSE |
|---|---|---|
| Linear Regression | 0.71 | 5.00 |
| Ridge Regression | 0.71 | 5.00 |
| Random Forest | 0.88 | 3.29 |
| Refined Random Forest | 0.74 | 4.80 |

## Conclusion

The original Random Forest model achieved the strongest predictive performance overall. However, feature importance analysis suggested that fare-related variables contributed substantial information closely tied to completed trip characteristics.

After removing fare-related variables, the refined Random Forest model provided a more realistic interpretation of the independent factors influencing taxi trip duration, with trip distance emerging as the strongest predictor.

These results demonstrate the importance of both predictive performance and thoughtful feature selection when developing machine learning models.