# deep-learning-challenge
UofT Bootcamp

## Overview


The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Using knowledge of machine learning and neural networks, and the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.


## Results:


- What variable(s) are the target(s) for your model? 
“IS_SUCCESSFUL” variable is our target in our model.

- What variable(s) are the features for your model? ? The rest of the data, excluding “EIN” and “NAME” will be used as our features: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS and ASK_AMT. 

- What variable(s) should be removed from the input data because they are neither targets nor features? “EIN” and “NAME” will be removed as it is an identification column.

- How many neurons, layers, and activation functions did you select for your neural network model, and why? I decided to use 2 hidden layers with 90 and 45 neurons. I chose 90 as the rule of thumb, was indicated that i should be 2 to 3 times the number of input features. This one has 43 so I rounded up and the 2nd hidden was on the close enough to the number of input features. 

- Were you able to achieve the target model performance? No.


