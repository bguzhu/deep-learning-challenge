# deep-learning-challenge
Deep learning

#The report should contain the following:

#Overview of the analysis: 
Explain the purpose of this analysis.

The purpose of this analysis is to create and optimize a neural network (deep learning) model that predicts whether applicants will be successful if funded by Alphabet Soup. 

#Results: Using bulleted lists and images to support your answers, address the following questions:

#Data Preprocessing

What variable(s) are the target(s) for your model?

The target variable is the IS_SUCCESSFUL column.

What variable(s) are the features for your model?

The feature variables for the model are status, ask amount, application type, income amount, special consideration, name, use_case, organization, affiliation, and classification.

What variable(s) should be removed from the input data because they are neither targets nor features?

EIN (Employee Identification Number) should be removed from the input data. It isn't necessary for the analysis.

#Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

For the model, there are 3 layers each containing many neurons. The first two activation functions are relu and the last is sigmoid. The optimized model has 4 layers with many neurons. The first activation function is relu and the last three are sigmoid. 

Were you able to achieve the target model performance?

I wasn't able to achieve higher than 75% accuracy in model performance. 

What steps did you take in your attempts to increase model performance?

To increase model performance, I added an additional hidden layer with the first layer using the relu activation function. I also used the ASK_AMT column to bin and replace categorical variables. For training the model, I increased the number of epochs to 150.

#Summary: 

Summarize the overall results of the deep learning model.

Overall, the deep learning model has an accuracy of around 74% and loss of information approximately 55%. Even though the model doesn't meet the 75% requirement, it is able to predict correctly 74% of the time.

Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

Another model that can be used is random forests because this is another type of machine learning model that can perform and address classification problems.
