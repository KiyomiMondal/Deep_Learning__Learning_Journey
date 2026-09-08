# Why Convolutions?

## Problem with Fully Connected Networks

For images:

100 × 100 image = 10,000 pixels

A fully connected network requires enormous numbers of parameters.

Problems:

- High memory usage
- Slow training
- Overfitting

---

## Local Connectivity

Nearby pixels are more related than distant pixels.

CNNs exploit this property.

---

## Parameter Sharing

Same filter scans entire image.

Instead of learning thousands of weights:

Learn one filter.

Benefits:

- Fewer parameters
- Better generalization

---

## Translation Invariance

Object remains detectable even if shifted.

Example:

Cat on left side
Cat on right side

CNN still recognizes it.

---

## Hierarchical Feature Learning

Layer 1 → Edges

Layer 2 → Shapes

Layer 3 → Object Parts

Layer 4 → Complete Objects

---

## Summary

Convolutions reduce parameters, improve feature extraction, and make image processing efficient.
