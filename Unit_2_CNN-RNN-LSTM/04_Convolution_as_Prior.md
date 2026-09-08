# Convolution and Pooling as Strong Prior

## What is a Prior?

A prior is an assumption built into the model.

CNNs assume:

- Nearby pixels are related
- Patterns can appear anywhere

---

## Locality Prior

Pixels close together contain useful information.

Example:

Edges
Corners
Textures

---

## Translation Prior

Object can appear anywhere.

CNNs detect it regardless of position.

---

## Pooling Prior

Exact location is less important than existence.

Example:

Detecting a cat.

Whether cat is slightly left or right often doesn't matter.

---

## Why Important?

These assumptions help CNNs:

- Learn faster
- Use fewer parameters
- Generalize better

---

## Summary

Convolution and pooling introduce useful assumptions that make learning efficient.
