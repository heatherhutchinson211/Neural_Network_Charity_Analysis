# Neural_Network_Charity_Analysis
## Overview
The purpose of this analysis was to use neural networks in order to create binary classifications.  These classifications were then used to predict the funding success of Alphabet Soup for applicants.  Data was compliled, trained, and then evaluated in a model. 

## Results
### Data Preprocessing
During preprocessing, I visualized the value counts of Classification as well as Application Type, as shown below:
![Application Type]()
![Classification]()


#### - What variable(s) are considered the target(s) for your model?
  
    The targets for this model are chosen by the IS_SUCCESSFUL column.
    
#### - What variable(s) are considered to be the features for your model?

    The following columns were considered features for this model:
    
      APPLICATION_TYPE            
      AFFILIATION                  
      CLASSIFICATION              
      USE_CASE                     
      ORGANIZATION                 
      STATUS                       
      INCOME_AMT                   
      SPECIAL_CONSIDERATIONS       
      ASK_AMT
      
#### - What variable(s) are neither targets nor features, and should be removed from the input data?
    The "EIN" and "NAME" columns were neither targets nor features, and thus were removed from the dataset. 
    
    
### Compiling, Training, and Evaluating the Model
#### - How many neurons, layers, and activation functions did you select for your neural network model, and why?
    I tried a few different methods, but I ultimately ended up using 2 hidden layer with 80 and 30 neurons.  
#### - Were you able to achieve the target model performance?
    Unfortunately, I was not able to achieve the 75% model performance. 
#### - What steps did you take to try and increase model performance?
    I tried to achieve model performance by changing the number of hidden layers, neurons, and activation functions a few different times. 

## Summary
  I think that continuing to test out different methods would help me to achieve a better accuracy score. I might also try using a different method of testing in the future. 
