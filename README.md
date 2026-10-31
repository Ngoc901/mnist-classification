# MNIST Classification (PyTorch Basics Practice)

A deep learning practice project implementing handwritten digit classification on the classic MNIST dataset using PyTorch.

---

## 1. Overview
- **Goal:** Practice foundational computer vision concepts, PyTorch neural network building blocks (`torch.nn`), data loading (`DataLoader`), loss functions, optimization, and evaluation metrics.
- **Framework:** PyTorch & Torchvision
- **Dataset:** MNIST (28x28 grayscale images of handwritten digits 0–9)

---

## 2. Structure
```
mnist_classification/
├── notebooks/          # Jupyter / Google Colab notebooks
├── data/               # Local dataset cache (ignored in Git)
├── .gitignore
└── README.md
```

---

## 3. How to Run
1. Open the notebook in **Google Colab** or locally in VS Code / Jupyter Lab.
2. Ensure PyTorch and Torchvision are installed:
   ```bash
   pip install torch torchvision matplotlib
   ```
3. Run all cells to download MNIST, train the model, and view predictions.
