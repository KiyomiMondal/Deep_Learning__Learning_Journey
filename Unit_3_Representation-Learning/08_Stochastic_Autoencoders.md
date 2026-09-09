# Stochastic Autoencoders

## Overview

Stochastic Autoencoders introduce randomness into the latent representation.

Most important example:

Variational Autoencoder (VAE)

---

## Why Needed?

Standard Autoencoders:

Learn fixed representations.

VAEs:

Learn probability distributions.

---

## Variational Autoencoder (VAE)

Encoder outputs:

- Mean (μ)
- Variance (σ²)

Latent vector is sampled from this distribution.

---

## Architecture

Input
↓
Encoder
↓
μ, σ
↓
Sampling
↓
Latent Vector
↓
Decoder
↓
Output

---

## Advantages

- Generate new data
- Learn smooth latent spaces
- Useful for generative AI

---

## Applications

- Image Generation
- Face Generation
- Drug Discovery
- Data Augmentation

---

## Difference from Autoencoder

Autoencoder:
- Deterministic

VAE:
- Probabilistic

---

## Summary

Stochastic Autoencoders model latent representations as probability distributions.
