# Learning XOR

## XOR Problem

XOR (Exclusive OR) returns:

| A | B | XOR |
|---|---|-----|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

---

## Why XOR is Important

The XOR problem demonstrates the limitation of linear models.

A single-layer perceptron cannot solve XOR.

---

## Linear Separability

Classes are linearly separable if one straight line can separate them.

AND and OR are linearly separable.

XOR is NOT linearly separable.

---

## Why Single-Layer Perceptron Fails

Perceptrons create linear decision boundaries.

XOR requires non-linear decision boundaries.

---

## Solution

Introduce hidden layers.

Input
↓
Hidden Layer
↓
Output

The hidden layer transforms data into a representation where XOR becomes linearly separable.

---

## Role of Activation Functions

Without activation functions:

Multiple layers collapse into one linear transformation.

With non-linear activations:

Complex functions like XOR can be learned.

---

## Significance

The inability of perceptrons to learn XOR motivated the development of multilayer neural networks and backpropagation.

---

## Summary

XOR proves that hidden layers and non-linear activations are necessary for solving complex problems.
