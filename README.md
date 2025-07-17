# Overfitting-Prevention
Various Regularization Techniques to Prevent Overfitting

Purpose: The purpose of this assignment is to build and train multilayer fully connected dense layer neural network with different techniques to prevent overfitting. 

In this project, you will use given data sets, but you will experiment with techniques to prevent overfitting. 
In the notebook, you are already given different model architectures
A.	Model 1 with no dropout
B.	Model 2 with no dropout
C.	Model 2 with drop out
D.	Model with L1 regularization 
E.	Model with L2 regularization
F.	Model with L1L2 regularization
G.	Model with Batch normalization

-	In Model 1 (A), increase the number of nodes in the hidden layer to 100 and add drop out layer with rate 0.25. Train the new model.
-	Train the models D, E, F, and G (early stopping should be applied) using the same training parameters used with the “dropout” technique in the notebook. Report predictions on the testing set from these four models. 
Plot the training/validation loss and accuracy vs epochs from the four training procedures.
