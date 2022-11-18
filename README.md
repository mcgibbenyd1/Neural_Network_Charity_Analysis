# Neural_Network_Charity_Analysis

# Overview
This analysis is to produce a binary classifier to predicti whether applicants will be successful if funded by Alphabet Soup.

The relavant CSV from the Alphabet Soup's business team, contains more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

#### Data Preprocessing

- What variable(s) are considered the target(s) for your model?

"IS_SUCCESSFUL" was the dependant variable reviewed to be predicted.

- What variable(s) are considered to be the features for your model?

43 columns from the categorical transformations to binary from encoding the data

- What variable(s) are neither targets nor features, and should be removed from the input data?

The unique identifier fields ("EIN" and "NAME")

#### Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why?

hidden_nodes_layer1 = 90, activation="relu"
hidden_nodes_layer2 = 10, activation="sigmoid"
1 Output of activation ="sigmoid"

- Were you able to achieve the target model performance?

Accuracy: 0.7305 was the best able to be reached. 75% was the goal but unable to be achieved

- What steps did you take to try and increase model performance?

Increase neurons, changing the loss type, adding layers and change the activation types

## Summary

Within 50 epochs, a accuracy of 73% was achieved. Possible a tuning with hyper parameter would benefit at optimizing the model to meet the desired goal
