# Wine Classification using MLP on MS Excel

The objective of this project is to understand the basic of Multli Layer Perceptron, a feedforward Artificial Neural Network. The MLP consists of 3 layer of nodes,an input layer, a hidden layer and an output layer. The hidden layer and the output layer uses an non-linear activation function or a squashing fucntion to limit node output.

This is an example of a pattern recognition problem where we would like to create a neural network that not only classifies the known wines properly, but can generalize to accurately classify wines.

The 13 wine attributes will act as inputs to a neural network, and the respective target for each will be a 3‐element vector with a 1 for each winery: #1, #2 or #3. Therefore the net has three outputs with activation function.

The data set consists of 178 instances and each one is described with 13 characteristics given above. The dataset can be found in the UCI Machine Learning Repository: http://archive.ics.uci.edu/ml/datasets/Wine

The process can be explained as follows:

1. Initialize the network (random weights)
2. Present a pattern and compute its output
3. Compute the error (difference between expected and obtained output) across allpatterns.
4. Change weights to reduce the error
5. Goto Step 2 if error is large
