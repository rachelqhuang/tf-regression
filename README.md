# tf-regression
A simple implementation for regression problems using Python 2.7 and TensorFlow

* [train_test_data.py](train_test_data.py) is a script that preprocesses a data file into the necessary train and test set arrays for TensorFlow. It includes functions to convert categorical variables into dummies, convert string values into Python compatible strings, and remove outliers

* [train_neural_network.py](train_neural_network.py) contains the steps to build and evaluate a TensorFlow neural network. Bulk of code from PythonProgramming.net with further enhancements including cost function tracking, leaky ReLU implementation, and elastic net regularisation (from [TensorFlow Machine Learning Cookbook](https://github.com/nfmcclure/tensorflow_cookbook) by @nfmcclure)

Here are some additional resources if you are looking to explore neural networks and TensorFlow more extensively:

1. Deep Learning with Neural Networks and TensorFlow series by PythonProgramming.net
2. MNIST for ML Beginners by TensorFlow.org
3. Calculus on Computational Graphs: Backpropagation by @colah (available on his [GitHub](http://colah.github.io/)) 
4. [tensorflow_tutorials](https://github.com/pkmital/tensorflow_tutorials) by @pkmital 
5. Neural Networks, Manifolds, and Topology by @colah (available on his [GitHub](http://colah.github.io/))
6. Implementing a Neural Network from Scratch by @dennybritz (available on WildML.com)
7. Efficient Backprop by LeCun et al., 1998 
8. Practical Recommendations for Gradient-Based Training of Deep Architectures by Bengio, 2012
