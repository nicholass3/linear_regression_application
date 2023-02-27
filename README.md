# linear_regression_application
A project of applying Linear Regression with MSE as cost function.
Predict the value of “Y” using all the different combinations of the 3 input features to find the best possible setup for prediction: 
- Single input – single output:
  o Input [X1] => Output[Y] 
  o Input [X2] => Output[Y] 
  o Input [X3] => Output[Y]
- Double input – single output:
  o Input [X1, X2] => Output[Y] 
  o Input [X2, X3] => Output[Y] 
  o Input [X1, X3] => Output[Y]
- And finally, triple input – single output: 
  o Input [X1, X2, X3] => Output[Y]
  
Objectives:
Train a linear regression model with gradient descent using the training set and each of the feature combinations outlined above for a total of 7 models.
  1. Use the MSE (Mean Square Error) function as your cost function.
    o Choose weight update mechanism m = 100
    o Stopping condition: “maximum of 1000 gradient descent iterations” 
    or “cost function stops improving for 10 iterations in a row on the early stopping set", whichever happens first.
    o Select the learning rate as either 0.1, 0.01, or 0.001. Try and see which one gives the best results.

Deliverables:
- Plot the cost function, J(theta), against the iteration count, for training, validation (early stopping) and testing sets ON THE SAME PLOT for each of the 7 models.
Your script, should output 7 plots with 3 individual curves in each showing how the cost function changes during training for training/validation/testing sets.
- Report the MSE on the test set (AVERAGED ACROSS ALL TEST SAMPLES) for each of the 7 models.
- Plot the “actual” versus “predicted” output on the test set for your best performing feature combination for each of the observations in the test set. 
(i.e., your x-axis will have 100 ticks)
