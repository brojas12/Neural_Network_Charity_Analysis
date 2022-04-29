# Neural_Network_Charity_Analysis

## Overview of the analysis

    Explain the purpose of this analysis.
    
    The purpose of this analysis is to use the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.


## Results


*Data Preprocessing*

* What variable(s) are considered the target(s) for your model?

        The IS_SUCCESSFUL column contains binary data referring to whether or not the charity donation 
        was used effectively. This variable is then considered as the target for our deep learning 
        neural network.

* What variable(s) are considered to be the features for your model?

        The columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, 
        STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the features for our model.

* What variable(s) are neither targets nor features, and should be removed from the input data?

        The EIN and NAME columns are neither targets nor features and should be removed from 
        the input data.

*Compiling, Training, and Evaluating the Model*

* How many neurons, layers, and activation functions did you select for your neural network model, and why?
        This deep-learning neural network model is made of two hidden layers with 80 and 30 neurons respectively. The input 
        
        data has 43 features and 25,724 samples. We used the activation function ReLU for the hidden layers and the sigmoid 
        
        on the output layer.

* Were you able to achieve the target model performance?

        Unfortunately, the model accuracy is under 75%. Therefore, this is not a satisfying performance to help predict the
        
        outcome of the charity donations.

* What steps did you take to try and increase model performance?
        
        To increase the performance of the model,
        
        We added a third hidden layer,
        
        We increased the number of neurons on the hidden layers and used the model with three hidden layers,
        
        We changed the activation function on the output layer to Linear. 


## Summary

    The deep learning neural network model did not reach the target of 75% accuracy. Considering that this target level is average. 
    It is safe to say the model is not outperforming.The situation is that of a binary classification, it might help to 
    try a supervised machine learning model such as the Random Forest Classifier that will allow us to combine multiple decision 
    trees and generate an output to test against our deep learning model. 
