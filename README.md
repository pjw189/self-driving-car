# Self-Driving Car
Implementation of a Deep Q-Learning artificial neural network (ANN) to model a self-driving car using PyTorch.

The car will not be given any rules on how to operate in the environment before hand - it will have to figure everything out on it's own.

Deep Q-Learning is the result of combining Q-Learning with an Artificial Neural Network. The states of the environment are encoded by a vector which is passed as input into the Neural Network. Then the Neural Network will try to predict which action should be played, by returning as outputs a Q-value for each of the possible actions. Eventually, the best action to play is chosen by either taking the one that has the highest Q-value, or by using a Softmax function for the action selection policy.

# Getting Started

The following packages are required before running.

Linux and Max users:
conda install pytorch==0.3.1 -c pytorch
conda install -c conda-forge kivy

And Windows users, in the anaconda prompt:
conda install -c peterjc123 pytorch-cpu
conda install -c conda-forge kivy
