### House Price Prediction

This repository contains a Python implementation of a linear regression model to predict house prices based on features such as square footage and the number of bedrooms and bathrooms. The model is trained on a dataset obtained from Kaggle.

#### Problem Statement
The goal is to develop a model that accurately predicts house prices using relevant features. This model can be valuable for individuals and organizations involved in the real estate industry.

#### Dataset
The dataset used for training and testing the model can be found here-  https://www.kaggle.com/c/house-prices-advanced-regression-techniques/code. It consists of various features related to residential properties, including:

- Lot area
- Number of bedrooms
- Number of bathrooms
- Total basement area
- Sale price

#### Implementation
The Python script `PRODIGY_ML_01` contains the implementation of the linear regression model. The script follows these main steps:

1. **Data Loading and Inspection**: The dataset is loaded into a Pandas DataFrame, and basic information about the dataset is displayed.
2. **Data Cleaning and Preparation**: Data cleaning steps, such as handling missing values and duplicates, are performed. Numerical features are selected, and a correlation matrix is generated to identify relationships between features and the target variable (sale price).
3. **Model Training**: The dataset is split into training and testing sets. A linear regression model is trained using the training data.
4. **Model Evaluation**: The trained model is evaluated using mean squared error (MSE) and R-squared metrics to assess its predictive performance.
5. **Prediction**: The model is used to predict the prices of new houses based on their features.
6. **Cross-Validation**: Cross-validation is performed to assess the model's performance and generalization ability.

#### Usage
To run the script and train the model:


#### Requirements
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Plotly


This project is licensed under the MIT License. Feel free to use and modify the code for your own projects. If you find it helpful, consider giving it a star!
