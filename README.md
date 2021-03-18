# Neural_Network_Charity_Analysis

/Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, 
address the following questions.

/Data Preprocessing
/What variable(s) are considered the target(s) for your model?
/What variable(s) are considered to be the features for your model?
/What variable(s) are neither targets nor features, and should be removed from the input data?
/Compiling, Training, and Evaluating the Model
/How many neurons, layers, and activation functions did you select 
for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take to try and increase model performance?
Summary: Summarize the overall results of the deep learning model. 
Include a recommendation for how a different model could solve this 
classification problem, and explain your recommendation.


Alphabet Soup's business team has some information Beks needs to create
a binary classifier to predict whether certain applicants will be
successful if they are monetarialy supported by their team. By using 
machine learning and neural networks Beks and I will analyze a large CSV 
to find which components led to an organization's success. 

The following variables are considered features for the model:

* EIN and NAME—Identification columns
* APPLICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special consideration for application
* ASK_AMT—Funding amount requested
* IS_SUCCESSFUL—Was the money used effectively

These features were not needed:
* EIN and NAME—Identification columns

The focus of this analysis is targeted upon this column:
* IS_SUCCESSFUL—Was the money used effectively