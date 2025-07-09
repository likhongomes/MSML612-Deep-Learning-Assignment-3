# MSML612-Deep-Learning-Assignment-3

LSTM is widely used because the architecture overcomes the vanishing and exploding gradient problem that plagues all recurrent neural networks, allowing very large and very deep networks to be created. 

In this assignment, you will develop an LSTM recurrent neural network model which will address a simple sequence prediction problem of learning the alphabet. That is, given a letter of the alphabet, predict the next letter of the alphabet. This is a simple sequence prediction problem that once understood can be generalized to other sequence prediction problems like time series prediction and sequence classification.

Hence, you will build a simple LSTM to learn how to predict the next character in the alphabet given the context of just one character. You will frame the problem as a random collection of one-letter input to one-letter output pairs. Below is a set of steps as a guideline to build and validate the LSTM model for this assignment.

1. Import all necessary libraries and define the dataset such as
alphabet = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"

2. Create mapping of characters to integers (0-25) and the reverse
3. Prepare the dataset of input to output pairs encoded as integers
4. Ensure that you reshape X to be [samples, time steps, features]
5. Normalize the data
6. One hot encode the output variable (turn it into categorical)
7. Create and fit the model
8. Summarize performance of the model by printing its accuracy
9. Demonstrate the model predictions by feeding in and printing the input and predicted output characters 
10. First, do the experiments with two LSTM layers with the same parameters. Then vary the number of layers and compare how the performance varies. Include some plots/graphs/tables to support your claim.
11. Vary the hyperparameters-- learning rate, hidden size, number of layers. How varying these parameters change the overall accuracy? Include some plots/graphs/tables for each of the hyper parameters explaining how you have picked the optimal one.

Reasonable performance should generate an accuracy of over 80%. 

Please upload your python code (.py or .ipynb) and report(.pdf) by the due date.
