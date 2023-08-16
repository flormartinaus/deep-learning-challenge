# deep-learning-challenge
 
## Summary 
The primary objective of this deep learning challenge was to create a binary classifier capable of predicting the probability of applicants achieving success after receiving funding from Alphabet Soup, a charitable organization. By leveraging features within the provided dataset, a variety of machine learning techniques were employed to train and evaluate the model's effectiveness. The ultimate goal of the challenge was to enhance the model's performance to achieve an accuracy score of 75% or higher.

## Data processing
During the preprocessing phase, I applied binning or bucketing to handle infrequent instances within the APPLICATION_TYPE and CLASSIFICATION columns. Consequently, the categorical data underwent transformation into numeric representations through the utilization of encoding methodology. Subsequent steps involved the division of data into distinct sets for features and targets, as well as for training and testing purposes. Lastly, the data underwent scaling to ensure consistency in its distribution.

## First Model 
It has two hidden layers with 60 and 40 neurons, respectively, both using the ReLU activation function, and an output layer with a single neuron and sigmoid activation. Accuracy is 72.5%

## First Optimisation
It has different activation functions for the hidden layers, such as 'relu' or 'leaky_relu', and also different number of neurons to see if they improve the model's performance but it didn't. Accuracy is 72.7%

## Second Optimisation
I tried changing the neural network code to include dropout layers and to give the hidden layers L2 regularisation. Accuraccy did not improved, 72.3%

## Third Optimisation
I tried modifying the neural network code to implement dropout layers and add L2 regularization to the hidden layers: 
1.	Increased the number of units in the first hidden layer to 128.
2.	Increased the number of units in the second hidden layer to 64.
3.	Added a third hidden layer with increased complexity, consisting of 128 units.
No improvements on accuracy resuting in 72.7%

## Conclusions

At this point, I was unable to get to 75% accuracy. A neural network's success depends on the careful interplay of several different aspects, including data quality, model architecture, hyperparameters, and optimisation techniques. In the future, I must carefully examine the quantity and quality of the data, test different model designs, and assess the preprocessing of data, which includes normalisation and the management of missing information. These actions are a vital component of our ongoing attempts to improve the performance of our model.

