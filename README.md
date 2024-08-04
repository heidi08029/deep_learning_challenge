Overview of the analysis: Explain the purpose of this analysis.
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, we use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
Results: 
Data Preprocessing

What variable(s) are the target(s) for your model?
IS_SUCCESSFUL—Was the money used effectively

What variable(s) are the features for your model?
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested

What variable(s) should be removed from the input data because they are neither targets nor features?
EIN and NAME—Identification columns

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
I start with 2 hidden layers and also tried 3 layers and relu function and change the number of epochs from 100 to 150 but i was still not able to achieve 75%. The best model I have i
