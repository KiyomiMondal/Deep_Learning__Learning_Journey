# Types of Convolutions

## Standard Convolution

Most common convolution.

Kernel slides over image.

---

## 1×1 Convolution

Uses 1×1 filters.

Purpose:

- Channel reduction
- Feature combination

Used in:

- GoogleNet
- ResNet

---

## Dilated Convolution

Adds gaps between kernel elements.

Benefits:

- Larger receptive field
- Fewer parameters

---

## Depthwise Convolution

Applies one filter per channel.

Used in MobileNet.

---

## Pointwise Convolution

1×1 convolution following depthwise convolution.

---

## Separable Convolution

Depthwise + Pointwise.

Benefits:

- Faster
- Fewer parameters

---

## Transposed Convolution

Used for upsampling.

Applications:

- Image Generation
- Segmentation

---

## Grouped Convolution

Channels divided into groups.

Used in ResNeXt.

---

## Summary

Different convolution types improve efficiency, accuracy, or scalability.
