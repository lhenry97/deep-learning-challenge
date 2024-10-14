# deep-learning-challenge

## Overview

The purpose of this analysis is to assist the nonprofit foundation Alphabet Soup in selecting applicants for funding with best chance of success in their ventures. Machine learning and neural networks is used with the dataset to create a binary classifier that is able to predict whether applicants are going to be successful if funded by Alphabet Soup. The data used for this was the charity_data.csv file which contains data points on individuals identification, application type, affiliation, classification, use case, organisation, status, income classification, speacial considerations for application, funding amount requested and whether it was successful.


## Results
### Data Preprocessing

The variable that is the target for the model is "IS_SUCCESSFUL".

The variables that are the features for the model is:
APPLICATION_TYPE
AFFILIATION
CLASSIFICATION
USE_CASE
ORGANIZATION
STATUS
INCOME_AMT
SPECIAL_CONSIDERATIONS
ASK_AMT

The variables that should be removed are EIN and NAME.

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

A number of attempts were made to obtain an accuracy of higher than 75%. This model was unsuccessful and the highest percentage obtained was 72.52% accuracy. The number of neurons used was 181 and 4 layers were used. The activation function was relu for the input layer, sigmoid for the hidden layers and sigmoid for the output layers. These were selected through trial and error to see if possible to achieve a higher accuracy.

Were you able to achieve the target model performance?

The target model performance was unable to be achieved.
        
What steps did you take in your attempts to increase model performance?

Steps taken to attempt to increase model performance was changing the activation function, increasing the number of neurons and increasing the number of hidden layers.


## Summary

The overall results saw an accuracy of 72.52%, 2.48% off the target accuracy. This indicates that there is room for improvement in this model to obtain a better accuracy such as removing less important features. An alternative model that could be used to solve this problem would be random forest due to its ability to handle large amounts of data and its ability to give insights into which features are more influential in predicting the target. 
