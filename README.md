# DigitRecognition
FinalYearProject
-Meghana,Pavan,Kavya
Start with the neuralNetwork.m code in the Code folder. This neuralNetwork.m uses many functions, many of which are defined in the other .m files in the Code folder. Adequate comments are provided in the right places for understanding the code.
neuralNetwork.m -> Main code

.idx3-ubyte -> Contains the original training images and labels

loadMNISTImages.m, loadMNISTLabels.m -> Loads the training images and their labels from the original idx3-ubyte files

displayData.m -> Displays 2D data in a nice grid

nnCostFunction.m -> Implements the neural network cost function for a two layer neural network which performs classification

sigmoidGradient.m -> Returns the gradient of the sigmoid function

sigmoid.m -> Computes sigmoid function

randInitializeWeights.m -> Randomly initialize the weights of a layer of neurons in the neural network

checkNNGradients.m -> Creates a small neural network to check the backpropagation gradients

validationCurveHoldout.m -> Generates the training and validation errors needed to plot a validation curve that we can use to select regularization parameter

fmincg.m -> a function which works similarly to "fminunc"

predict.m -> Predicts the label of an input given a trained neural network

predictExternalImage.m -> Predicts what digit is contained in an external image for a trained neural network

predictPercentExternalImage.m -> Predicts what digit is contained in an external image, along with the probability given a trained neural network

neuralNetworkWeights - HU200_EP1000_R0.1.mat, neuralNetworkWeights-98.35.mat, savedNeuralNetworkWeights.mat -> Saved Neural Network weights
