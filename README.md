# Neural_Network_Charity_Analysis

## Overview

In this module, we used our knowledge of neural networks and machine learning to compile, tain and optimize our neural network model using the data that we were provided. This process is necessary to provide Beks a binary classifier that will give us a prediction of applicants who would be successful if being funded by AlphabetSoup.

## Data Processing

- The variable that was considered a target in our analysis was the IS_SUCCESSFUL column.
- The variables that are considered to be the features for my model are the columns that were not dropped, excluding our target.
- Variables that were neither targets nor features were the identification columns, and we dropped them from our model.

## Compiling, Training, and Evaluating the Model

- The original model contains two hidden layers. The first layer contains 80 neurons and the second one contains 30 neurons. In our first two layers, we have our "relu" activation function. In our output layer, we have our "sigmoid" activation function.
 <img width="926" alt="NN1" src="https://user-images.githubusercontent.com/85713532/140383145-3b29e551-082c-493c-bf66-40c33b5e5520.png">
- We did not achieve our target model performance. I only achieved 72 percent on the model. 
 <img width="622" alt="NN2" src="https://user-images.githubusercontent.com/85713532/140383154-ad0be048-4c91-4767-97f6-41eb92e2efa4.png">
- I tried to increase the model performance by adding hidden layers, changing the actiavtion layers , changing the number of neurons in the hidden layers and changing the epochs.

## Summary

The best model performance percentage I received was 72.6 percent. I was not able to achieve over 75 percent for the model, however, if we were to include more data and treat more missing and outlier values, it could achieve the 75 percent that we are looking for.
