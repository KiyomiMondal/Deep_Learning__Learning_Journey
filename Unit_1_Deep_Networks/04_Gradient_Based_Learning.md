# Gradient-Based Learning

## Overview

Neural networks learn by minimizing a loss function.

The optimization process relies on gradients.

---

## Loss Function

Measures prediction error.

Examples:

### Mean Squared Error (MSE)

MSE = (1/n) Σ(y - ŷ)²

### Cross Entropy Loss

Used for classification tasks.

---

## What is a Gradient?

Gradient indicates:

- Direction of steepest increase
- Magnitude of change

To minimize loss we move opposite the gradient.

---

## Gradient Descent

Parameter update:

θ = θ - η ∇J(θ)

where:

- θ = parameters
- η = learning rate
- J = loss function

---

## Learning Rate

Controls step size.

Small:
- Slow learning

Large:
- May overshoot optimum

---

## Types of Gradient Descent

### Batch Gradient Descent

Uses entire dataset.

### Stochastic Gradient Descent (SGD)

Uses one example at a time.

### Mini-Batch Gradient Descent

Uses small batches.

Most commonly used.

---

## Local Minima

Deep networks often have non-convex loss functions.

Optimization aims to reach low-loss regions.

---

## Summary

Gradient-based learning updates network parameters using derivatives of the loss function.
