# Neural Networks from Scratch

## What is a Neural Network?

A neural network is a series of algorithms that attempt to recognize underlying relationships in a set of data through a process that mimics the way the human brain operates. Neural networks can adapt to changing input; so the network generates the best possible result without needing to redesign the output criteria.

![Neural Network Diagram](https://github.com/anshh-arora/Neural-Network-From-Scratch/blob/main/nn.png)

## Why Use Neural Networks in Data Science?

Neural networks are powerful tools for data science because they can model and interpret complex data patterns. They are particularly useful for:

- **Pattern Recognition**: Identifying patterns and trends in large datasets.
- **Prediction and Forecasting**: Making accurate predictions based on historical data.
- **Classification**: Categorizing data into predefined classes.
- **Anomaly Detection**: Identifying unusual data points that may indicate errors or fraud.

## How Neural Networks Work

The working of a neural network involves several steps:

1. **Input Layer**: Receives the input data.
2. **Hidden Layers**: Process the input data through a series of transformations. Each layer consists of neurons, which apply weights to the inputs and pass them through an activation function.
3. **Output Layer**: Produces the final output of the network based on the transformations performed by the hidden layers.
4. **Training**: Adjusts the weights using a process called backpropagation to minimize the error in the output. This is done by computing the loss function and updating the weights to reduce the loss.

### Activation Functions

Activation functions introduce non-linearity into the network, allowing it to learn complex patterns. Common activation functions include:

- **ReLU (Rectified Linear Unit)**: `f(x) = max(0, x)`
- **Sigmoid**: `f(x) = 1 / (1 + exp(-x))`
- **Tanh (Hyperbolic Tangent)**: `f(x) = tanh(x)`

### Loss Functions

Loss functions measure how well the neural network's predictions match the actual data. Common loss functions include:

- **Mean Squared Error (MSE)**: Used for regression tasks.
- **Cross-Entropy Loss**: Used for classification tasks.

## About This Repository

In this repository, I have built a neural network from scratch and also compared it with the Multi-Layer Perceptron (MLP) implementation from the `scikit-learn` library. This comparison highlights the differences and similarities in performance and implementation between a custom neural network and a library-based one.

## How to Clone the Repository

To clone this repository, use the following command in your terminal:

```bash
git clone https://github.com/anshh-arora/Neural-Network-From-Scratch.git
