Overview: The purpose of this analysis is to show the way I tried to train a neural network model.

Results: I tried 6 different models to try to get a model with 75% accuracy, but I was unable to.

*Data Preprocessing*
1. What variable(s) are the target(s) for your model?
- The target variable is the "IS_SUCCESSFUL" column
2. What variable(s) are the features for your model?
- The feature variables were created by dropping the "IS_SUCCESSFUL" column, so every other column was the feature variables. 
3. What variable(s) should be removed from the input data because they are neither targets nor features?
- "EIN" and "NAME" were dropped because they aren't targets or features. 

*Compiling, Training, and Evaluating the Model*
1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
-I started with 8 and 5 at random, and then I was randomly adding more nodes and more layers in attempt to get higher accuracy. 
2. Were you able to achieve the target model performance?
-No, I was not able to get a model with accuracy of 75% or higher. Most of my models were around 73% accurate. 
3. What steps did you take in your attempts to increase model performance?
- I mostly changed up the amounts of nodes and layers, but I also tried changing the activation function. 

Summary:
My model was around 73% accurate in predicting if applicants would be successful if funded by Alphabet Soup. Since I didn't reach the desired accuracy, there is most likely some different kind of data clean up that I could have done to get a higher accuracy rate. 
