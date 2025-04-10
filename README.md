# Celsius_to_Fehrenhiet_Tensorflow
Model using tensorflow which converts celsius into fehrenhiet
The training process starts with a forward pass, where the input data is fed to the neural network. 
Then the model applies its internal math on the input and internal variables to predict an answer.
The input is the degrees in Celsius, and the model predicts the corresponding degrees in Fahrenheit.
Once a value is predicted, the difference between that predicted value and the correct value is calculated. This difference is called the loss, and it's a measure of how well the model performed the mapping task. 
The value of the loss is calculated using a loss function, which we specified with the loss parameter when calling model.compile().
After the loss is calculated, the internal variables (weights and biases) of all the layers of the neural network are adjusted, so as to minimize this loss — that is, to make the output value closer to the correct value.
This optimization process is called Gradient Descent. The specific algorithm used to calculate the new value of each internal variable is specified by the optimizer parameter - we used the Adam optimizer.
