# Neural Network Charity Analysis

## Project Overview
The purpose of the project was to design a neural network to create a binary classification model that can predit if udnded organizations will be successful based on the features in the dataset.

## Results
### Data Preprocessing
-The variable considered the target of our model is the 'IS_SUCCESSFUL' column in our dataset. It is what we are trying to predict.
-The variable considered to be the features of our model are the other columns within our dataset.
-The variable that are neither targets nor features are the 'EIN' and 'NAME' columns. Those were removed from our data.

### Compiling, Training, and Evaluating the Model
-The original model had two node layers with 75 and 40 nodes respectively with 'relu' activations which led to 72.4% accuracy. The first optimization had nothing of change which led to 63.3% accuracy. The second optimization had four node layers of 100, 70, 40, and 10 respectively with 'relu' activations which led to 72.6% accuracy. The third optimization had 3 node layers with 80, 50, 30 nodes respectively with 'sigmoid' activations which led to 72.5% accuracy.
-I was not able to achieve the target model performance.
-I increased the number of node layers, changed the number of nodes in each layer, as well as changing the activation for the nodes in an attempt to increase accuracy.

## Summary
The highest accuracy achieved was 72.6% after various changes.
