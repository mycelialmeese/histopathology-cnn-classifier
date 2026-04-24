# Histopathology Image Classifier

A convolutional neural network trained to classify histopathology images, built as part of a deep learning Kaggle competition.

## Overview

This project explores CNN architectures for image classification on a biomedical imaging dataset. The notebook covers iterative model development — including architecture comparisons, overfitting diagnostics, and the use of skip connections to improve performance.

## Approach

- Baseline CNN trained from scratch; evaluated against validation loss and accuracy
- Explored multiple architectures, identifying overfitting as the primary failure mode
- Applied skip connections (ResNet-style) to improve gradient flow and generalization
- Iterated on hyperparameters, dropout, and data augmentation strategies

## Tech Stack

- **Framework:** PyTorch
- **Environment:** Jupyter Notebook (Kaggle)
- **Key concepts:** CNNs, skip connections, overfitting diagnostics, image augmentation

## Context

This was a one-credit module project completed as part of an M.S. in Data Science. The focus was on hands-on model iteration and understanding failure modes — not a production-ready pipeline.

## Results

Achieved competitive classification accuracy on the held-out test set. Key takeaway: skip connections meaningfully reduced validation loss compared to a flat CNN baseline.
