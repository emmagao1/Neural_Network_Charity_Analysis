# Neural_Network_Charity_Analysis

## Overview of the analysis: Explain the purpose of this analysis.
Use machine learning and neural networks to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. We analyzed dataset of more than $34,000 organizations that have received funding from Alphabet Soup over the years. We processed data for Neural Network Model, we complied, trained, and evaluated the model and then we optimized the model for improving accuracy.


## Results: Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing

1. What variable(s) are considered the target(s) for your model? 
*IS_SUCCESSFUL column in the data set.

2. What variable(s) are considered to be the features for your model? 
*Other than IS_SUCCESSFUL column, every other columns are considered features for my model.

3. What variable(s) are neither targets nor features, and should be removed from the input data? 
*There are two variables being dropped: EIN and Name. Reason for dropping those two variables is that those variables do not provide informative data for us to determine successful funding. 

### Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why? 
* There are 80 neurons in 1st layer and 30 neurons in 2nd layer. There are 5,981 total parameters.
![1](https://github.com/emmagao1/Neural_Network_Charity_Analysis/blob/main/Images/1.PNG)

* There are 100 neurons in 1st layer, 80 neurons in 2nd layer and 50 neurons in 3rd layer. There are 16,281 total parameters.
![2](https://github.com/emmagao1/Neural_Network_Charity_Analysis/blob/main/Images/2.PNG)

2. Were you able to achieve the target model performance? 
* We were not able to achieve 75% accuracy rate. Both original and Optimized model achieved 73% accuracy.

3. What steps did you take to try and increase model performance?
* Dropped 2 more columns
* Added additional neurons
* Added additional layers
* Increased tensorflow epocs 

## Summary
We have achieved 73% accuracy for both models. Instead of using Neural Network models, we can use Random Forest Classification model as it's more robust and accurate.
