# Feedforward Neural Networks

## Overview

A Feedforward Neural Network (FNN) is the simplest neural network architecture.

Information flows in one direction:

Input → Hidden Layer(s) → Output

No cycles or feedback connections exist.

---

## Architecture

Input Layer
↓
Hidden Layer(s)
↓
Output Layer

---

## Components

### Neuron

A neuron computes:

z = w₁x₁ + w₂x₂ + ... + wₙxₙ + b

Output:

a = f(z)

where:

- x = input
- w = weights
- b = bias
- f = activation function

---

## Weights

Weights determine the importance of inputs.

Larger weights have more influence on output.

---

## Bias

Bias shifts the activation function.

Without bias many functions cannot be represented effectively.

---

## Hidden Layers

Hidden layers learn intermediate features.

Example:

Image → Edges → Shapes → Objects

---

## Output Layer

Depends on task:

### Regression

Single linear output

### Binary Classification

Sigmoid output

### Multi-class Classification

Softmax output

---

## Universal Approximation Theorem

A neural network with one hidden layer can approximate any continuous function given enough neurons.

---

## Advantages

- Learns non-linear relationships
- Flexible architecture

---

## Disadvantages

- Computationally expensive
- May overfit

---

## Summary

Feedforward Neural Networks are the foundation of Deep Learning and consist of layers of neurons connected through weights.
