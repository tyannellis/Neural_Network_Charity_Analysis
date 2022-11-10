# Neural_Network_Charity_Analysis

## Overview 
The purpose of this analysis was to create a binary classifier to determine if charites will succeed if they are given funding. 

## Preprocessing 
* The target variable is 'IS SUCCESSFUL" 
* The features 
APPLICATION_TYPE,
AFFILIATION,
CLASSIFICATION,
USE_CASE,
ORGANIZATION,
STATUS,
INCOME_AMT,
SPECIAL_CONSIDERATIONS, and
ASK_AMT
* The EIN and NAME

## Compiling,Training,and Evaluating the Model

* The model has 2 hidden layers 
* 80 nuerons for the first layer and 30 for the second 
* The activation function for the outer layer is sigmoid   
* The hidden layers use relu for teh activation function
* My model was not able to reach 75% accuracy
* To improve accuracy I dropped a featrue, added another hidden layer, and changed outer layer function to tanh.

## Summary 
The first model was 69%, after making changed the model went to 46%. Accuracy may have been improved by adding more data and dropping more features.
