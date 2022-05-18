# time_series_example

The scripts run in TensorFlow environment.
In this script I analize a univariate time series using different methods followint this process:

1. Defining used functions for each Neural Network type. 
2. Plot the serie and Holt Winter's projection
3. Run the Hult Winter's model
4. Run the 'Naive NN model'
5. Run 'Multilayer Perceptron Neural Networl model'
6. Run 'Convolutional Neural Network model'
7. Run 'LSTM Recurrent Neural Network model'
8. Run 'CNN - LSTM Convolutional - Recurrent Neural Network model'
9. Run 'ConvLSTM Convolutional 2D Neural Network model'
10. Summarize the squared mean error and standar deviation for the best model

For testing purposes, some functions are not reused when the different models are run. In live execution, only the user-defined function to fit the model (and the "difference" function when required) should be different.
