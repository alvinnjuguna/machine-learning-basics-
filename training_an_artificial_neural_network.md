# Training an Artificial Neural Network

Training an Artificial Neural Network (ANN) means teaching the network
how to make correct predictions using data.

## Key Concepts in Training

### 1. Weights and Bias
- Weights control the importance of inputs
- Bias helps shift the activation function

These values are updated during training.

### 2. Loss Function
The loss function measures how wrong the network’s predictions are.

Common examples:
- Mean Squared Error (MSE)
- Cross-Entropy Loss

Lower loss means better performance.

### 3. Backpropagation
Backpropagation is the process of updating weights by:
- Calculating the error at the output
- Propagating the error backwards
- Adjusting weights to reduce the error

### 4. Gradient Descent
Gradient Descent is an optimization algorithm used to minimize the loss.

It updates weights using the rule:

## Conceptual Python Example
# simple weight update example
weight = 0.5
learning_rate = 0.01
gradient = 0.2

weight = weight - learning_rate * gradient

