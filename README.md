# Analyze Australia Car Market Data Summary 
## 1. Introduction : 
This project is to get valuable information such as 'most popular car' and also to make a model to predict the price of the cars using various features such year, car brand, and mileage. The dataset was sourced from Kaggle and contains over 17000 data. The dataset can be access with https://www.kaggle.com/datasets/lainguyn123/australia-car-market-data 

## 2. Data Cleaning and Preprocessing :
- Drop the missing value and also '-' value from the dataset
- Drop the unused columns
- Change the value type from the column to numerical

## 3. Exploratory Data Analysis (EDA) : 
- Drop one feature when there is multicollinearity (In this case, 'Year' and 'Kilometres')
- 'Price' and 'Year' had a positive correlation

## 4. Modeling and Evaluation
- Linear Regression: R-squared = 0.54, MSE = 2.6e+08
- Random Forest: R-squared = 0.71, MSE = 1.6e+08

## 5. Key Insights 
- Random Forest was more effective model for price prediction than Linear Regression
- Brand was the most important features

## 6. Conclusion: 
The Random Forest model performed well. For further improvements can be made testing with another model and compare the result.