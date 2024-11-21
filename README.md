
# Task 3: Car Selling Price Prediction

This project predicts the selling price of cars using a dataset containing various car-related features. The workflow includes data preprocessing, model training using a Random Forest Regressor, and evaluating model performance with various metrics.

## Features
- Data cleaning and encoding categorical features using `LabelEncoder`.
- Training and testing split for predictive analysis.
- Model training using **Random Forest Regressor**.
- Evaluation metrics:
  - **R² (R-Squared)** score
  - **Mean Absolute Error (MAE)**
  - **Root Mean Squared Error (RMSE)**
  - Cross-validation scores
- Visualizations:
  - Actual vs Predicted values
  - Feature Importance
  - Correlation Heatmap

## Dataset
The dataset used is car data.csv, which contains the following columns:

- Year: Manufacturing year of the car.
- Selling_Price: Price at which the car is being sold (target variable).
- Other columns: Various features influencing the selling price (categorical and numerical)

## Results
### Model Performance Metrics:
- R² score: Measures the proportion of the variance explained by the model.
- MAE: Average magnitude of the errors.
- RMSE: Square root of the average squared difference between predicted and actual values.
### Feature Importance:
- A barplot displaying the relative importance of each feature in predicting the selling price.
### Correlation Heatmap:
- A heatmap visualizing the correlations between features in the dataset.

## Outputs
- Scatterplot: Actual vs Predicted Selling Prices
- Lineplot: Predicted vs Actual Selling Prices over Index
- Feature Importance Barplot: Highlights the most significant features for prediction.
- Heatmap: Visual representation of feature correlations.
