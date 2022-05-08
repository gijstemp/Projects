# Predicting start-up succes

This is a project that I did during my studies. In a group with four others we went on our way to predict start-up success based on different features. This project is split into two notebooks:
 - Exploratory Analysis
 - Predictive Modelling
 
## Exploratory Analysis
In this notebook we first processed the data to be usable. We added secondary data form external sources and made sure that it was usable. Thereafter we did an in depth analysis on all of the features so as to better understand which features would be important for predicting the succes of start-ups (based on total funding).

## Predictive Modelling
After teh initial exploratory analysis we went on our way to create predictive models. First we did some feature engineering to get all the data correct for use in our models. Thereafter we created a few models to compare their performance, as there is no free lunch. After creating the models we did conducted hyperparameter tuning to get the best parameters for our predictions. The models were then compared to each other to get the final best performing model. 
The models we created and compared were:
 - OLS
 - Lasso Regression
 - Random Forest
 - Support Vector Regression
 - Gradient Boosting
 - KNN
