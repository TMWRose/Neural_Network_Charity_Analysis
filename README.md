# Neural_Network_Charity_Analysis

## Overview

In this module we helped Becks, a data scientist and programmer for the nonproft foundation Alphabet Soup, analyze data to find high risk organizations the company shouldn't donate to. We used a deep learning neural network to analyze all inputs to produce a mathmatically sound decision. 

## Results

### Data Preprocessing

1. **What variable(s) are considered the target(s) for your model?**

  - The target was IS_SUCCESSFUL
  
2. **What variable(s) are considered to be the features for your model?**

  - APPLICATION_TYPE and CLASSIFICATION were the features used
  
3. **What variable(s) are neither targets nor features, and should be removed from the input data?**

  - EIN and NAME were removed from the data
  
### Compiling, Training, and Evaluating the Model

1. **How many neurons, layers, and activation functions did you select for your neural network model, and why?**

  - I had 8 nodes for level one and 5 nodes for level two. My output layer only had a sigmoid activation function. That's what worked for the example in the module practice, so I used it for the challenge. 
  
2. **Were you able to achieve the target model performance?**

  - Unknown, when I ran the code it got stuck on the training section of the code with SVM fit foor 4 hours, so I had to kill the run. I assume that it would eventually work though, but I do not have time to confirm at the moment. 
  
3. **What steps did you take to try and increase model performance?**

  - I added training variables, used SVM fit, decreased the number of notes, and added checkpoints.
  
## Summary
