# Neural_Network_Charity_Analysis

Overview

The purpose of the Neural Network Model Analysis is to use our knowledge and understanding of machine learning and neural networks to help Beks, using Alphabet Soup’s dataset, to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

Using our understanding of Pandas and Scikit-Learn StandardScaler, we reprocessed the dataset in order to compile, train, and evaluate the neural network model. 

Results:

Data Processing
•	What variable(s) are considered the target(s) for your model? In this model, we are targeting the IS_SUCCESSFUL column as we are trying to determine if applicants will be successful if funded by Alphabet Soup
•	What variable(s) are considered to be the features for your model? The features for our model are: 
o	APPLICATION_TYPE
o	AFFILIATION
o	CLASSIFICATION
o	USE_CASE
o	ORGANIZATION
o	STATUS
o	INCOME_AMT
o	SPECIAL CONSIDERATIONS
o	ASK_AMT 
o	IS_SUCCESSFUL
•	What variable(s) are neither targets nor features, and should be removed from the input data? EIN and NAME are identification columns and are neither targets nor features and were removed from the data.

Compiling, Training, and Evaluating the Mode
•	How many neurons, layers, and activation functions did you select for your neural network model, and why? There are 80 neurons in the first layer and 30 neurons in the second layer. Both hidden layers have “relu” activation function and “sigmoid” activation function was used for the outer layer. 
•	Were you able to achieve the target model performance? Unfortunately, the target model did not achieve the 75% performance target.
Model Accuracy.png
 
•	What steps did you take to try and increase model performance? To increase the performance of the model, I added a third hidden layer with 20 neurons and used “sigmoid” activation function, Unfortunately, it did not improve the model performance. 

Summary

The accuracy level for this model was at 72.7%, which is under the 75% target performance. I believe the performance could be increased if we had more data to work with. Unfortunately, due to the performance of this model, we cannot use the model to predict whether applicants will be successful if funded by Alphabet Soup

