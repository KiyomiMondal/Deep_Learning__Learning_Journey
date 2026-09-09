# Regularized Autoencoders

## Overview

Regularized Autoencoders add constraints that force better representations.

---

## Why Regularization?

Without constraints:

Autoencoder may simply memorize input.

Regularization prevents this.

---

## Sparse Autoencoder

Encourages most neurons to remain inactive.

Benefits:

- Feature selection
- Sparse representations

---

## Denoising Autoencoder

Input is corrupted with noise.

Network learns:

Noisy Input → Clean Output

Benefits:

- Noise robustness
- Better feature learning

---

## Contractive Autoencoder

Penalizes sensitivity to input changes.

Benefits:

- Stable representations

---

## Comparison

| Type | Purpose |
|--------|----------|
| Sparse | Sparse features |
| Denoising | Noise removal |
| Contractive | Robust features |

---

## Applications

- Feature extraction
- Representation learning
- Denoising

---

## Summary

Regularized Autoencoders learn more robust and meaningful representations.
