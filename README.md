Recurrent Neural Network using LSTM to Evaluate Random Number Generator’s Effectiveness

A simple RNN model is designed with LSTM (Long Short Term Memory) is used to predict the next hex number with a given array of consecutive random hex numbers.

Two simple RNN models are presented as follows:
1.	Input -> LSTM -> Dense;
2.	Input -> Conv1d -> Relu -> Pooling -> LSTM -> Dense

The dataset is acquired from https://qrng.anu.edu.au/RainHex.php. There are 327399 (317399 for training, 10000 for testing) hex numbers in this dataset. 
