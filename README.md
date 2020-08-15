# Degree-Estimator
•	This project coming after the exploratory students degree analysis which it forms the conclusion that the math course it was difficult for all the students. I created a tool that estimate degrees( MAE 3.2 grade) in order to help the students strategy before the math exams.

•	I found the data set at Kaggle with over than a 1000 students grades

•	Optimized Linear, Lasso and Random Forest Regression in Order to reach the best model

## Model Building

Initially I transformed the categorical variables into dummy variables. In addition I split the data into training and test split with a test size of 20%.

I tried tree different models and evaluated them with the Mean Absolute Error. I choose the MAE because is easy to interpret the results and it fits nice at that type of problems.

As I mentioned above I tried: 

•	Multiple Linear Regression

•	Lasso Regression

•	Random Forest

## Model performance
Linear Regression: MAE = 4.22

Lasso Regression: MAE = 4.20

Random Forest: MAE = 4.63
