# Hidden Units and Activation Functions

## Hidden Units

Hidden units learn intermediate representations.

Example:

Image
↓
Edges
↓
Shapes
↓
Objects

---

## Why Hidden Units?

Without hidden units:

Only simple patterns can be learned.

With hidden units:

Complex patterns become learnable.

---

## Activation Functions

Introduce non-linearity.

Without activation functions:

Network becomes a linear model.

---

## Sigmoid

σ(x) = 1 / (1 + e⁻ˣ)

Range:

0 to 1

Advantages:

- Probability interpretation

Disadvantages:

- Vanishing gradients

---

## Tanh

tanh(x)

Range:

-1 to 1

Advantages:

- Zero-centered

Disadvantages:

- Vanishing gradients

---

## ReLU

ReLU(x) = max(0,x)

Advantages:

- Simple
- Fast
- Reduces vanishing gradient problem

Most widely used.

---

## Leaky ReLU

LeakyReLU(x)

Allows small negative outputs.

Prevents dead neurons.

---

## Softmax

Converts outputs into probabilities.

Used in multi-class classification.

---

## Choosing Activations

Hidden Layers:
- ReLU
- Leaky ReLU

Output Layer:
- Sigmoid (binary classification)
- Softmax (multi-class)
- Linear (regression)

---

## Summary

Activation functions allow neural networks to learn non-linear relationships.
