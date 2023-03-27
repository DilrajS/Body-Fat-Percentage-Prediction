# Body Fat Percentage Prediction using Random Forest Regression

This project is a demonstration of how to use random forest regression to predict body fat percentage. The dataset used in this project is the Body Fat Percentage dataset from Kaggle, which contains 252 observations of male individuals with various body measurements and their corresponding body fat percentages.

## Prerequisites

To run this notebook, you will need:

- Python 3
- Jupyter Notebook or Google Colab

## Installation

1. Download the Jupyter Notebook file (body-fat-percentage-prediction.ipynb) from the repository.
2. Open the Jupyter Notebook file in Jupyter Notebook or Google Colab.
3. Run the notebook cell by cell to replicate the analysis and results.

## Dataset

The Body Fat Percentage dataset contains 252 observations and 17 variables. The variables are:

- Density: Body density determined by underwater weighing
- Bodyfat: Body fat percentage determined by underwater weighing
- Age: Age in years
- Weight: Weight in pounds
- Height: Height in inches
- Neck: Neck circumference in inches
- Chest: Chest circumference in inches
- Abdomen: Abdomen circumference in inches
- Hip: Hip circumference in inches
- Thigh: Thigh circumference in inches
- Knee: Knee circumference in inches
- Ankle: Ankle circumference in inches
- Biceps: Biceps (extended) circumference in inches
- Forearm: Forearm circumference in inches
- Wrist: Wrist circumference in inches

## Analysis

The analysis and modeling process is as follows:

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Model Development
- Model Evaluation and Validation

The selected model for this project is Random Forest Regression. Model performance is evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared. A residual analysis is performed to check the assumptions of the model. The model is then validated using k-fold cross-validation and grid search to test different hyperparameters.

## Results

The final model achieved a mean absolute error of 0.1570 on the test set. The best hyperparameters for the model are the default values provided by scikit-learn's RandomForestRegressor function.

## Conclusion

Random forest regression is an effective method for predicting body fat percentage based on various body measurements. The default hyperparameters provided by scikit-learn's RandomForestRegressor function work well for this dataset. Further research could explore other regression techniques and feature engineering methods to improve model performance.
