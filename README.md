# Neural_Network_Charity_Analysis

Overview of the loan prediction risk analysis:

Our goal is the building and training of a neural network meant to predict what organizations secured funding.  This all with the intention to determine
what organizations should be given funding.

Results:

Summary:

Data Preprocessing
What variable(s) are considered the target(s) for your model?
The variable IS_SUCCESSFUL, Which refers to if the charity was successful in aquiring funding.

What variable(s) are considered to be the features for your model?
APPLICATION_TYPE,	AFFILIATION,	CLASSIFICATION,	USE_CASE,	ORGANIZATION,	STATUS,	INCOME_AM,	SPECIAL_CONSIDERATIONS,	ASK_AMT,

What variable(s) are neither targets nor features, and should be removed from the input data?
The EIN	and NAME variables are not needed for the model.

Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
5 Layers, 428 Neurons and the ReLu activation function.  The dataset had 34299 and considering the number of features it seemed the model
would require more neurons and layers from the initial attempt

Were you able to achieve the target model performance?
We were unfortunately unable to get the targetd performance albiet being very close.

What steps did you take to try and increase model performance?
I adjusted the bucketing of certain features, created bins for the Ask_Amount variable and added more neurons and additional layers
in order to improve accuracy.


There is a summary of the results (2 pt)

There is a recommendation on using a different model to solve the classification problem, and justification (3 pt)
I was unable to meet the performance target of the model and that is enough for me to recommend another model.  Perhaps a Random Forest model could yield 
better results as it does work similarly  to neural networks with less concern for choosing layers and neurons.
