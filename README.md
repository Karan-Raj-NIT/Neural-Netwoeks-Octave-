# Neural-Netwoeks-Octave-
Building a Neural Network from scratch using Octave

2.1 Model representation
 
 Our neural network has 3 layers { an input layer, a hidden layer and an output layer. Recall that our inputs are pixel values of digit images.
 Since the images are of size 20 by 20, this gives us 400 input layer units (excluding the extra bias unit which always outputs +1). As before,
 the training data will be loaded into the variables X and y. You have been provided with a set of network parameters (theta(1);theta(2))
 already trained by us. These are stored in ex3weights.mat and will be loaded by ex3 nn.m into Theta1 and Theta2 The parameters have dimensions 
 that are sized for a neural network with 25 units in the second layer and 10 output units (corresponding to the 10 digit classes).
 
2.2 Feedforward Propagation and Prediction
 
 Now we will implement feedforward propagation for the neural network. We will need to complete the code in predict.m to return the neural network's
 prediction. We should implement the feedforward computation that computes h_theta(x(i)) for every example i and returns the associated predictions.
 Similar to the one-vs-all classification strategy, the prediction from the neural network will be the label that has the largest output
 (h_theta(x))k. 
 You should see that the accuracy is about 97.5%. After that, an interactive sequence will launch displaying images from the training set one at a 
 time, while the console prints out the predicted label for the displayed image. 
