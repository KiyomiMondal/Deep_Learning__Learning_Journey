# Recurrent Neural Networks (RNN)

## Overview

RNNs are designed for sequential data.

Examples:

- Text
- Speech
- Time Series

---

## Why Not CNNs?

CNNs process inputs independently.

Sequences require memory.

---

## Hidden State

RNN maintains hidden state:

hₜ

Stores information from previous steps.

---

## Architecture

Inputₜ
↓
Hidden Stateₜ
↓
Outputₜ

---

## Formula

hₜ = f(Wₓxₜ + Wₕhₜ₋₁)

---

## Applications

- Language Modeling
- Translation
- Speech Recognition

---

## Problems

### Vanishing Gradient

Gradients become too small.

### Exploding Gradient

Gradients become too large.

---

## Solutions

- LSTM
- GRU
- Gradient Clipping

---

## Summary

RNNs process sequential data by maintaining memory through hidden states.
