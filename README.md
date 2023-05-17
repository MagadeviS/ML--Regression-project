# ML--Regression-project

# Project summary:

In this project, we train a model to predict the number of bike rentals at any hour of the year given the weather conditions.Regression techniques Decision Tree, Random Forest, Gradient Boosting Regressor, XGB Regressor are used to predict.

## Data Pipeline:

**Exploratory Data Analysis (EDA):** In this part we have done some EDA on the features to see the trend.

**Data Processing:** In this part we went through each attributes and encoded the categorical features.

**Model Creation:** Finally in this part we created the various models. These various models are being analysed and we tried to study various models so as to get the best performing model for our project.

This statistical data analysis shows interesting outcomes in prediction method and also in an exploratory analysis. First of all, we do EDA on the dataset and observe the following.

Heat map shows Temperature is highly correlated.
Most number of bikes are rented on time 5pm to 9pm of the day and in morning at 8 pm.
Most numbers of Bikes were rented in summer, followed by autumn, spring, and winter.
Most number of bikes are rented on Working day instead of holiday.

## Conclusion:

Comparing all regression moddel, Thus Gradient Boosting Regression(GridSearchCV), Random forest(GridSearchCV) gives good r2 scores.

On Random Forest Regression model, with hyperparameter tuning we got r2 score as 90% on training data and 86% on test data.

On Gradient Boosting Regression model, with hyperparameter tuning we got r2 score as 92% on training data and 89% on test data.
