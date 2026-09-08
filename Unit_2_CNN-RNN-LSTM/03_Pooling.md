# Pooling

## Overview

Pooling reduces spatial dimensions of feature maps.

It helps:

- Reduce computation
- Reduce overfitting
- Increase robustness

---

## Max Pooling

Selects maximum value.

Example:

Input:

1 3
5 2

Output:

5

---

## Average Pooling

Computes average value.

Example:

Input:

1 3
5 2

Output:

2.75

---

## Global Average Pooling

Computes average of entire feature map.

Often used before classification layers.

---

## Advantages

- Reduces memory usage
- Provides translation invariance
- Speeds up training

---

## Disadvantages

- Information loss

---

## Summary

Pooling compresses feature maps while retaining important information.
