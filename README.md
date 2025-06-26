# ElevateLabs_Task3_Linear Regression
# Housing Price Prediction using Linear Regression

This project applies **Simple and Multiple Linear Regression** to predict housing prices based on features like area, number of bedrooms, bathrooms, etc.

## Objective
To understand and implement:
- Simple Linear Regression (Area vs Price)
- Multiple Linear Regression (using all features)
- Model evaluation using MAE, MSE, and R² score

## Dataset
[Kaggle Dataset – Housing Price Prediction]: (https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Steps Performed
1. Imported and preprocessed the dataset (one-hot encoding for categorical features).
2. Performed train-test split.
3. Trained a Linear Regression model.
4. Evaluated model using:
   - MAE (Mean Absolute Error)
   - MSE (Mean Squared Error)
   - R² Score
5. Visualized:
   - Scatter plot with regression line (Simple Linear Regression)
   - Coefficients of features

## Results
- R² Score: **0.65**
- MAE: ~₹970,000
- MSE: ~1.75 trillion
- Most influential features: `bathrooms`, `airconditioning_yes`, `hotwaterheating_yes`

## Key Learning
- Linear Regression works well for understanding relationships.
- Some nonlinear patterns and outliers can affect accuracy.
- Feature scaling wasn’t required here, but encoding categorical variables was essential.
