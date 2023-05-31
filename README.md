# Happy_monk.AI
## Artificial Neural Network from scratch
perceptron model is a class of artificial neural network that uses back propagation technique for training.
It has two layers of nodes. The hidden layer has 4, the input layer has 4 and the output layer has 3 neurons.
During training, all the weights and biases are updated after processing single training sample with the help
of stochastic training method. The update_param uses learning rate of 0.01 and momentum factor of 0.001. 
The code is run for 1500 epochs. The activation function is multiple The performance of classification is measured using confusion matrix. 
The code computes specificity, sensitivity, precision, recall, accuracy and F-score. it has multiple functions like weight_params it 
initiate random weight for input data and for_prop function used for making forward propogation with input data,weight and bias and then to 
reduce error and update weights we have back_prop wich takes multipl arguments like weights,biases,train data and y_train
for evaluation i have used categorical cross entropy function and furth\
