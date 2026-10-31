# MNIST Classification (PyTorch Basics Practice)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1sHII8kFD9wZh9b2j0RrP_VnXdvEJytbm?usp=sharing)

A deep learning practice project implementing handwritten digit classification on the classic MNIST dataset using PyTorch.

---

## 1. Overview
- **Goal:** Practice foundational computer vision concepts, PyTorch neural network building blocks (`torch.nn`), custom data loading (`Dataset` & `DataLoader`), loss functions, optimization, and evaluation metrics.
- **Framework:** PyTorch & Torchvision
- **Dataset:** [teavanist/MNIST-JPG](https://github.com/teavanist/MNIST-JPG) (MNIST handwritten digits formatted as individual JPG images, split into training and testing folders)

---

## 2. Project Structure
```
mnist_classification/
├── notebooks/
│   └── mnist_classification_project.ipynb   # Main Jupyter / Google Colab notebook
├── data/                                    # Local dataset cache (ignored in Git)
├── .gitignore
└── README.md
```

---

## 3. How to Run

### Option A: In Google Colab (Recommended)
Click the badge above or use this link:  
👉 **[Open in Google Colab](https://colab.research.google.com/drive/1sHII8kFD9wZh9b2j0RrP_VnXdvEJytbm?usp=sharing)**

### Option B: Run Locally
1. Clone this repository:
   ```bash
   git clone <repo-url>
   cd mnist_classification
   ```
2. Install dependencies:
   ```bash
   pip install torch torchvision matplotlib pandas
   ```
3. Open the notebook in VS Code or Jupyter Lab:
   ```bash
   jupyter lab notebooks/mnist_classification_project.ipynb
   ```
