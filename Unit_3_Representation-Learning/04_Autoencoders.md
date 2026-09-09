# Autoencoders

## Overview

An Autoencoder is a neural network that learns to reconstruct its input.

---

## Architecture

Input
↓
Encoder
↓
Latent Space
↓
Decoder
↓
Output

---

## Components

### Encoder

Compresses input.

### Latent Space

Compact representation.

### Decoder

Reconstructs original input.

---

## Objective

Input ≈ Output

---

## Bottleneck

The latent layer contains fewer neurons.

Forces network to learn important features.

---

## Loss Function

Typically:

Mean Squared Error (MSE)

---

## Applications

- Compression
- Denoising
- Feature Learning
- Anomaly Detection

---

## Advantages

- Learns useful representations
- Unsupervised learning

---

## Summary

Autoencoders compress and reconstruct data while learning meaningful representations.
