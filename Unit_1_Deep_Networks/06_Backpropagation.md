# Backpropagation

## Overview

Backpropagation computes gradients of the loss function with respect to network parameters.

These gradients are used to update weights.

---

## Forward Propagation

Input
↓
Hidden Layers
↓
Output
↓
Loss

Produces prediction and computes error.

---

## Backward Propagation

Loss
↓
Gradient Calculation
↓
Weight Updates

---

## Chain Rule

Backpropagation uses the chain rule from calculus.

If:

y = f(g(x))

Then:

dy/dx = dy/dg × dg/dx

---

## Steps

### Step 1

Forward pass

### Step 2

Compute loss

### Step 3

Compute gradients

### Step 4

Update parameters

### Step 5

Repeat

---

## Why Backpropagation?

Efficiently computes gradients for millions of parameters.

Without backprop training deep networks would be impractical.

---

## Common Challenges

### Vanishing Gradient

Gradients become very small.

### Exploding Gradient

Gradients become extremely large.

---

## Solutions

- ReLU
- Batch Normalization
- LSTM
- Gradient Clipping

---

## Summary

Backpropagation is the core algorithm used for training neural networks.
