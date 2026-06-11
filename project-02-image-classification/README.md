# Project 2 — Image Classification with a CNN 🔢

Teaching a neural network to recognise handwritten digits (MNIST) — the first real step toward OCR.
Same 7-step ML workflow as Project 1, now with neural networks and a training loop you write yourself.

## What this project teaches
**Carried over (drilled again):** the 7-step workflow, classification vs regression, EDA + class balance,
train/val/test split & leakage, normalisation as scaling, loss-minimisation, overfitting vs underfitting.

**New:**
- Neural networks and **CNNs** — convolutions, ReLU, pooling, logits
- The **5-step training loop** (zero_grad → forward → loss → backward → step) — written from scratch
- Optimizers, learning rate, epochs, batches (gradient descent mechanics)
- Cross-entropy loss, argmax predictions, confusion matrix
- Saving/loading a model (`torch.save`) for deployment

## Hands-on elements
- You write: the forward pass, the training loop, and the accuracy function (scaffold + solution)
- You debug: a planted "missing `zero_grad()`" bug that breaks training silently
- 🔮 Predict-before-you-run checkpoints
- 🏭 A refactor into clean, deployable functions + model persistence

## Dataset
MNIST (70,000 handwritten digit images), downloaded automatically by `torchvision`.

## How to run
**VS Code / local:**
```bash
pip install -r requirements.txt
```
Open `image_classification.ipynb`, select your Python kernel, run top to bottom.
Trains on CPU in a few minutes; uses a GPU automatically if available.
(Prefer free GPU? Upload the notebook to Google Colab.)

## Skills demonstrated
`PyTorch` · `CNNs` · `deep learning` · `training loops` · `model evaluation` · `confusion matrix` · `model persistence`

---
*Project 2 of my AI learning journey. Next: OCR — reading sequences of characters from images.*
