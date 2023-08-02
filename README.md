# deep-learning-challenge
**Overview**:
The purpose of this analysis is to create a deep learning model using neural networks to predict the success of applicants for funding by Alphabet Soup. The model is a binary classifier that determines whether an applicant will use the funding effectively (1) or not (0). By predicting the success of applicants, Alphabet Soup can focus its funding on ventures with the highest likelihood of success, maximizing the impact of their resources.
**Results:**
-Data Preprocessing:

The target variable for the model is the "IS_SUCCESSFUL" column, which indicates whether the funding was used effectively (1) or not (0).
Feature Variables: "APPLICATION_TYPE," "AFFILIATION," "CLASSIFICATION," "USE_CASE," "ORGANIZATION," "STATUS," "INCOME_AMT," "SPECIAL_CONSIDERATIONS," and "ASK_AMT."
Variables Removed: The "EIN" and "NAME" columns were removed.
-Compiling, Training, and Evaluating the Model:

Neurons, Layers, and Activation Functions: The selected neural network model architecture consists of two hidden layers with 128 and 64 neurons, respectively.
The target model performance was set to get an accuracy of 75% or higher on the testing data.
Attempts to Increase Model Performance:Adjusting the number of epochs and batch size
**Summary:**
The deep learning model achieved an accuracy of approximately 72.86% on the testing data. While this is a respectable performance, it did not meet the target of 75% accuracy. Further hyperparameter tuning and feature engineering might be necessary to improve the model's accuracy.
