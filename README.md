# Neural Network Charity Analysis
## Overview
### Purpose


## Results
**Data Preprocessing**

o	What variable(s) are considered the target(s) for your model?

The target for our deep learning neural network is the “IS_SUCCESSFUL” column. This determines whether or not the charity was effective. 

o	What variable(s) are considered to be the features for your model?

The features for our deep learning neural network include "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "INCOME_AMT", "SPECIAL_CONSIDERATIONS". We encoded these categorical variables, split them into training and testing datasets and standardized them. 

o	What variable(s) are neither targets nor features, and should be removed from the input data? 

We are dropping the “EIN” and “NAME” columns as they are identifying information and therefore not beneficial.


**Compiling, Training, and Evaluating the Model**

o	How many neurons, layers, and activation functions did you select for your neural network model, and why?

o	Were you able to achieve the target model performance?

No, I was unable to achieve the target accuracy of 75%. We came very close with 73% however this is not sufficient enough to predict the outcome of charity donations.

o	What steps did you take to try and increase model performance? 

In efforts to try and increase model performance we made three separate changes. The first was to add more neurons to the hidden layers. The second was to add a third hidden layer. And third was to use a different activation function. 


## Summary
### Findings
The goal of the deep learning neural network model was to reach 75% predictive accuracy or higher which theoretically seems highly attainable. In the original model we only achieved 73% accuracy. After attempting to the optimize the model through multiple means we still did not reach that 75% threshold. Attempt one involved adding more neurons to the hidden layers which still only yielded a 73% accuracy. Attempt two of adding another hidden layer yielded 72% accuracy. Attempt three of using a different activation function on the hidden layers yielded 72% accuracy as well. So clearly none of these attempts had any significant difference on the predictive accuracy.
### Recommendations
