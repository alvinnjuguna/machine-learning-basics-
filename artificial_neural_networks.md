# Artificial Neural Networks (ANN)

Artificial Neural Networks are inspired by the human brain.
They consist of layers of neurons that process data.

## Basic Structure
- Input Layer
- Hidden Layer(s)
- Output Layer

Each neuron:
- Receives input
- Applies weights
- Adds bias
- Uses an activation function

## Simple Python Example (Conceptual)

```python
def neuron(inputs, weights, bias):
    total = sum(i * w for i, w in zip(inputs, weights)) + bias
    return total
