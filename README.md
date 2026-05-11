# Delivery Time Prediction

Predicts food delivery time using a Random Forest Regressor.

## Dataset
Food Delivery Route Efficiency Dataset

## Approach
- Feature engineering: extracted hour/day from timestamps (Pandas), computed route complexity and avg speed (NumPy)
- Encoded categorical variables (traffic level, delivery mode, weather)
- Trained Random Forest Regressor (Scikit-learn, 100 estimators)

## Results
- MAE: 7.89 minutes
- RMSE: 10.05 minutes

## Key finding
Feature importance analysis revealed which factors most affect delivery time.
