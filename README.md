# Neural_Network_Charity_Analysis
## Overview
The purpose of this analysis was to use neural networks in order to create binary classifications.  These classifications were then used to predict the funsing success of Alphabet Soup for applicants.

## Results
### Data Preprocessing
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
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
- Were you able to achieve the target model performance?
- What steps did you take to try and increase model performance?
