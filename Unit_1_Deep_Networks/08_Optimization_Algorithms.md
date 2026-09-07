# Optimization Algorithms

## Goal

Optimization algorithms minimize the loss function by updating model parameters.

---

## Gradient Descent

Update rule:

θ = θ - η∇J(θ)

---

## Stochastic Gradient Descent (SGD)

Updates weights after every example.

Advantages:

- Fast updates
- Low memory

Disadvantages:

- Noisy updates

---

## Mini-Batch SGD

Uses small batches.

Most common approach.

---

## Learning Rate Decay

Gradually decreases learning rate during training.

Benefits:

- Stable convergence
- Better final performance

---

## Momentum

Accumulates previous gradients.

Velocity:

v = αv - η∇J

Update:

θ = θ + v

Benefits:

- Faster convergence
- Reduced oscillations

---

## Nesterov Momentum

Looks ahead before computing gradient.

More accurate updates.

---

## AdaGrad

Adapts learning rates for each parameter.

Good for sparse data.

Limitation:

Learning rate decreases too much.

---

## RMSProp

Improves AdaGrad.

Uses moving average of squared gradients.

---

## Adam

Most popular optimizer.

Combines:

- Momentum
- RMSProp

Advantages:

- Fast
- Stable
- Widely used

Typical parameters:

Learning Rate = 0.001

β₁ = 0.9

β₂ = 0.999

---

## Comparison

| Optimizer | Speed | Popularity |
|------------|--------|------------|
| SGD | Medium | High |
| Momentum | Fast | High |
| AdaGrad | Medium | Moderate |
| RMSProp | Fast | High |
| Adam | Very Fast | Very High |

---

## Summary

Optimization algorithms determine how neural network parameters are updated to minimize loss and improve learning.
