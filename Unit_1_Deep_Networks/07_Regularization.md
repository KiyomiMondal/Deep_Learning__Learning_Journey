# Regularization for Deep Learning

## What is Overfitting?

Overfitting occurs when a model memorizes training data instead of learning general patterns.

Training Accuracy = High

Test Accuracy = Low

---

## What is Regularization?

Techniques that reduce overfitting and improve generalization.

---

## L1 Regularization

Adds:

Loss + λ Σ|w|

Effects:

- Encourages sparse weights
- Feature selection

---

## L2 Regularization

Adds:

Loss + λ Σw²

Effects:

- Smaller weights
- Smoother models

Also called Weight Decay.

---

## Dropout

Randomly disables neurons during training.

Benefits:

- Prevents co-adaptation
- Reduces overfitting

---

## Early Stopping

Stop training when validation performance stops improving.

Prevents memorization.

---

## Data Augmentation

Creates new training examples.

Examples:

- Rotation
- Cropping
- Flipping
- Brightness adjustment

---

## Noise Robustness

Ability to perform well despite noisy inputs.

---

## Bagging

Train multiple models and combine predictions.

Example:

Random Forest

Benefits:

- Lower variance
- Better generalization

---

## Summary

Regularization techniques improve model performance on unseen data.
