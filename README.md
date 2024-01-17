# USA Housing Price Prediction Project

## Overview

This project focuses on predicting housing prices in the USA using a linear regression model. The dataset used in this project is named 'USA_Housing.csv' and contains various features related to housing.

## Procedures

### 1. Data Loading and Exploration

- The dataset is loaded using the pandas library.
- Initial exploration is performed by displaying the first few rows and summary statistics of the dataset.
- Information about the dataset, including data types and missing values, is examined.

### 2. Data Visualization

- A pairplot is created using seaborn to visualize relationships between numerical variables.
- The resulting plot is saved as 'output.jpg'.

### 3. Data Preprocessing

- Features and target variable are separated.
- The StandardScaler is used to standardize the features.

### 4. Data Splitting

- The dataset is split into training and testing sets using the train_test_split function from scikit-learn.

### 5. Model Building

- A linear regression model is created using scikit-learn's LinearRegression class.
- The model is trained on the training data.

### 6. Model Evaluation

- Predictions are made on the test set.
- The R-squared score is calculated to evaluate the model's performance.

### 7. Results Visualization

- A scatter plot is created to visualize the relationship between actual and predicted values.
- A histogram of the residuals is plotted to examine the distribution of errors.

### 8. Coefficients Display

- The coefficients of the linear regression model are displayed in a DataFrame.

## Conclusions

- The linear regression model has been successfully trained and evaluated.
- The R-squared score provides insight into the model's predictive performance.
- The coefficients of the model indicate the impact of each feature on the housing prices.

Feel free to explore the code and adapt it for your specific needs. If you have any questions or suggestions, please don't hesitate to reach out.
