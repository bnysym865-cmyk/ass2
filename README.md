/ass2
# Logistic Regression (Binary Classification) with Optimization Algorithms

This repository contains the implementation of Binary Logistic Regression from scratch using Python (`NumPy` and `Pandas`), comparing five different gradient-based optimization algorithms.

## Project Structure

* `1_Batch_GD.ipynb` — Logistic Regression trained using Batch Gradient Descent.
* `2_SGD.ipynb` — Logistic Regression trained using Stochastic Gradient Descent.
* `3_Mini_Batch_Gradient_Descent.ipynb` — Logistic Regression trained using Mini-Batch Gradient Descent.
* `RMSprop.ipynb` — Logistic Regression trained using RMSprop.
* `Adam.ipynb` — Logistic Regression trained using Adam Optimizer.
* `Logistic_Regression_Optimizers_Report.docx` — Detailed analysis and comparison report of the algorithms.

## Evaluation Metrics

Each optimizer is evaluated on the test set using Binary Cross-Entropy Loss and standard classification metrics:
* **Loss** (Binary Cross-Entropy)
* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**

## Requirements

* Python 3.x
* NumPy
* Pandas
