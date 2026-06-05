# Project 1 — California House Price Prediction 🏡

A from-scratch refresher on the **complete machine-learning workflow**, using a simple regression
problem so that every concept is visible and clearly explained.

## What this project teaches
The 7 universal steps that recur in *every* ML project:

1. **Frame the problem** — regression vs classification, features (X) vs target (y)
2. **EDA** — explore and understand data before modelling
3. **Train/test split** — generalisation, and why it's the heart of ML
4. **Preprocessing & data leakage** — scaling, and "fit on train, transform on both"
5. **Training a model** — what "learning" (loss + optimisation) really means
6. **Evaluation** — MAE / RMSE / R², and diagnosing overfitting vs underfitting
7. **Improvement** — Random Forests, cross-validation, feature importance

Every core concept is marked with 🔁 in the notebook because it returns in later projects.

## Dataset
The California Housing dataset, built into scikit-learn (no manual download).
Each row is a district; the target is median house value.

## How to run
**Option A — Google Colab (easiest, nothing to install):**
upload `house_price_prediction.ipynb` to [colab.research.google.com](https://colab.research.google.com) and run the cells top to bottom.

**Option B — Locally:**
```bash
pip install -r requirements.txt
jupyter notebook house_price_prediction.ipynb
```

## Key takeaways
- Machine learning is about **generalising to unseen data**, not memorising.
- **Data leakage** silently inflates scores — always fit preprocessing on the training set only.
- Diagnose model health with the **train-vs-test gap** (overfitting vs underfitting).

## Skills demonstrated
`Python` · `pandas` · `scikit-learn` · `regression` · `data visualisation` · `model evaluation` · `cross-validation`

---
*Project 1 of my AI learning journey. Next: image classification with neural networks.*
