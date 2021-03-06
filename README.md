### deep-learning-homework
# Write a Report on the Neural Network Model
For this part of the Challenge, you’ll write a report on the performance of the deep learning model you created for AlphabetSoup.
The report should contain the following:

## Overview of the analysis: Explain the purpose of this analysis.
The purpose of this project is to explore and implement neural networks using the TensorFlow platform in Python.

The steps to do the task:
- Preprocessing Data for a Neural Network Model
- Compile, Train, and Evaluate the Model
- Optimize the Model

## Data Preprocessing

1. What variable(s) are considered the target(s) for your model?
    - The target variable that was considered for this model: IS_SUCCESSFUL columns
2. What variable(s) are considered to be the features for your model?
    - Variable(s) were considered to be the features for this model: every columns except IS_SUCCESSFUL column which was dropped.
3. What variable(s) are neither targets nor features, and should be removed from the input data?
    - Variable(s) were neither targets nor features, and should be removed from the input data: EIN and NAME column.

## Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - This Neural Network Model has 2 Hidden Layers. First Hidden Layer has 80 neurons; the Second Hidden Layer has 30. The First and Second Hidden Layer have the *relu*      activation function and the activation function for the output layer is *sigmoid*.
2. Were you able to achieve the target model performance?
    - The model was not able to reach the target 75%. The accuracy for my model was 66%.
3. What steps did you take to try and increase model performance?
    - Removed one more features which is AFFILIATION column, updated the number of neuron for both hidden layer to 90 and 60. With this attempt, the accuracy went down to 66%.

**Summary:** Based on two attempted optimizations, the neural network accuracy ended up with 66%, which is lower than 73% accuracy of the initial neural network. Adding data to the dataset might help drive optimization or removing additional features.
