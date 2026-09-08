# Long Short-Term Memory (LSTM)

## Overview

LSTM is a special type of RNN.

Designed to solve:

- Vanishing Gradient
- Long-Term Dependency problems

---

## Key Idea

Maintain memory for long periods.

---

## Components

### Cell State

Long-term memory.

Cₜ

---

### Forget Gate

Decides what to remove.

---

### Input Gate

Decides what to store.

---

### Output Gate

Decides what to output.

---

## Architecture

Input
↓
Forget Gate
↓
Input Gate
↓
Cell State
↓
Output Gate
↓
Output

---

## Advantages

- Handles long sequences
- Better memory
- Stable training

---

## Applications

- Machine Translation
- Speech Recognition
- Text Generation

---

## Comparison

RNN:

Short memory

LSTM:

Long memory

---

## Summary

LSTM extends RNNs using gates that control information flow and memory retention.
