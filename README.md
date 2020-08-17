# Scores-Estimator
•	This project coming after the exploratory students scores analysis which forms the conclusion that the math course it was difficult for all the students. I created a tool that estimate scores( MAE 4.19 grade) in order to help the students strategy before the math exams.

•	I found the data set at Kaggle with over than a 1000 students scores in three different courses 

•	Optimized Multiple Linear, Lasso and Random Forest Regression in order to reach the best model

## Model Building

Initially I transformed the categorical variables into dummy variables. In addition I split the data into training and test split with a test size of 20%.

I tried tree different models and evaluated them with the Mean Absolute Error. I choose the MAE because is easy to interpret the results and it fits nice at that type of problems.

As I mentioned above I tried: 

•	Multiple Linear Regression

•	Lasso Regression

•	Random Forest

## Model performance
Linear Regression: MAE = 4.21

Lasso Regression: MAE = 4.19

Random Forest: MAE = 4.60
