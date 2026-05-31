# House Price Prediction using Linear Regression

## Overview

This project predicts house prices using Machine Learning techniques. The model is trained on housing data containing features such as square footage, number of bedrooms, bathrooms, lot size, garage size, year built, and neighborhood quality.

The objective of this project is to understand the complete Machine Learning workflow, from data preprocessing and exploratory data analysis to model training and evaluation.

## Dataset Features

* Square_Footage
* Num_Bedrooms
* Num_Bathrooms
* Year_Built
* Lot_Size
* Garage_Size
* Neighborhood_Quality

### Target Variable

* Price

## Project Workflow

1. Exploratory Data Analysis (EDA)
2. Data Cleaning
3. Correlation Analysis
4. Input-Output Splitting
5. Feature Standardization
6. Train-Test Split
7. Linear Regression Model Training
8. Model Evaluation

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Results

| Metric            | Score |
| ----------------- | ----- |
| R² Score          | 0.99  |
| Adjusted R² Score | 0.99  |

The model achieved excellent predictive performance on the dataset, indicating a strong relationship between the selected features and house prices.

## Key Learnings

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Correlation analysis
* Feature scaling using StandardScaler
* Linear Regression implementation
* Model evaluation using R² and Adjusted R²

## Repository Structure

├── House_Price_Prediction.ipynb
├── house_price_dataset.csv
├── README.md

## Future Improvements

* Compare multiple regression algorithms
* Hyperparameter tuning
* Feature engineering
* Deployment using Flask or Streamlit

## Author

Bhavik Vavadiya
