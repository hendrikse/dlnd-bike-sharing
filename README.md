# Predicting Bike-Sharing Data

In this real project, I built a neural network from scratch to carry out a prediction problem on a real dataset! By building a neural network from the ground up, it gave me a much better understanding of gradient descent, backpropagation, and other concepts that are important to know before moving on to higher-level tools such as PyTorch. 

## Overview of the different Steps

To get the final model the following steps are necessary:
1. Load the data
2. Identify and dummify categorical variables, and drop original categorical variables
3. Standardize continous variables
4. Drop unnecessary columns
5. Split the data into features and targets
6. Separate the data into training, validation, and test sets, taking into account the data type to prevent leakage
7. Train model using training data with different parameters and validate the performance using validation data
8. Apply the selected model to the test data
9. Reflect on the performance of the model.

## Credits

Credits go to Udacity as they provided the base structure and implementation steps. The initial repository can be found [here](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-bikesharing) 
