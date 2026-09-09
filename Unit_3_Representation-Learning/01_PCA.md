# Principal Component Analysis (PCA)

## Overview

Principal Component Analysis (PCA) is a dimensionality reduction technique that transforms high-dimensional data into a lower-dimensional space while preserving as much variance as possible.

---

## Why PCA?

Problems with high-dimensional data:

- Increased computational cost
- Storage requirements
- Noise
- Curse of dimensionality

PCA solves these issues by reducing dimensions.

---

## Key Concepts

### Variance

Measures how spread out data points are.

Higher variance means more information.

---

### Principal Components

New axes created by PCA.

Properties:

- Capture maximum variance
- Orthogonal to each other
- Ranked by importance

---

## Steps in PCA

1. Standardize data
2. Compute covariance matrix
3. Calculate eigenvalues and eigenvectors
4. Select top components
5. Transform data

---

## Eigenvalues

Represent amount of variance captured.

Higher eigenvalue = More information.

---

## Eigenvectors

Represent directions of maximum variance.

---

## Advantages

- Reduces dimensions
- Removes redundancy
- Faster training

---

## Disadvantages

- Information loss
- Harder interpretation

---

## Applications

- Data visualization
- Compression
- Noise reduction

---

## Summary

PCA transforms data into fewer dimensions while preserving maximum variance.
