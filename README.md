# Alphabet-Soup-Deep-Learning

## Overview:

The nonprofit foundation Alphabet Soup is seeking help to select applicants for funding with the best chance of success in their ventures. Using machine learning and neural networks, features in the provided dataset were used to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup. The first Model (Model_1) was analyzed with the code in the [Alphabet_Soup_Model1_Notebook.ipynb](https://github.com/adampaganini/Alphabet-Soup-Deep-Learning/blob/main/Model_1/Alphabet_Soup_Model1_Notebook.ipynb) notebook, while the model can be run from the [model1.h5](https://github.com/adampaganini/Alphabet-Soup-Deep-Learning/blob/main/Model_1/model1.h5) file. The data that trained the model contain more than 34,000 organizations that have received funding from Alphabet Soup along with the following columns:

- `EIN`
- `NAME`
- `APPLICATION_TYPE`
- `AFFILIATION`
- `CLASSIFICATION`
- `USE_CASE`
- `ORGANIZATION`
- `STATUS`
- `INCOME_AMT`
- `SPECIAL_CONSIDERATIONS`
- `ASK_AMT`
- `IS_SUCCESSFUL`

## Data Preprocessing

The target variable for this analysis is "IS_SUCCESSFUL", thus the analysis predicts the organizations that are likley to succeed given certain circumstances. The target variables are "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", and "ASK_AMT". The column "ORGANIZATION" was removed from the data set in an attempt to optimize results.

## Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why? Were you able to achieve the target model performance? While model optimization increased from 72.5% to 72.8% I did not reach the target of 75% after applying three optimization techniques.
To increase model performance additional neurons and hidden layers were added. 

## Results and conclusionsz

The accuracy of Model_1 did not reach beyond 73%, so the target of 75% accuracy was not accomplished in the alloted time frame. Various optimization techniques were employed such as a) using different activation functions for the hidden layers, b) dropping more or fewer columns, and c) adding or reducing number of epochs.  Consequently, no more models were able to be produced beyond Model 1 due to time constraints. 

