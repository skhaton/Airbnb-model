# Airbnb-model

In this code, I practice the evalution phase of the machine learning life cycle. I perform model selection for logictic regression to solve a classification problem. I worked with the arbnbData_train data set. My goal is to train a machine learning model that predicts whether an Airbnb host is a 'super host.' 

Here is the steps I took: 
- Build your DataFrame and define your ML problem:
    - Load the Airbnb "listings" data set
    - Define the label - what are you predicting?
    - Identify the features
- Create labeled examples from the data set
- Split the data into training and test data sets
- Train, test and evaluate a logistic regression (LR) model using the scikit-learn default value for hyperparameter 
- Perform a grid search to identify the optimal value of for a logistic regression model
- Train, test and evaluate a logisitic regression model using the optimal value of 
- Plot a precision-recall curve for both models
- Plot the ROC and compute the AUC for both models
- Perform feature selection
- Make your model persistent for future use
