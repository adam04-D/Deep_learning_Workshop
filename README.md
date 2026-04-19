# INSEA Innovation Edge — Deep Learning Workshop

Hands-on introduction to deep learning. Three notebooks take you from the math
foundations to training a real network, and finally to fine-tuning a
pre-trained model.

## Notebooks

1. **`01_math_interactive.ipynb`** — Math essentials
   Weights, loss, gradient descent, activations, and backprop — through
   interactive sliders and tiny NumPy examples. No PyTorch yet.

2. **`02_mnist_workshop.ipynb`** — Your first neural network (PyTorch)
   Build and train a small MLP to classify handwritten digits (MNIST).
   Every concept from notebook 1 maps directly to one line of PyTorch.

3. **`03_finetune_workshop.ipynb`** — Fine-tuning a pre-trained model
   Take a pre-trained DistilBERT and fine-tune it for sentiment
   classification on a small text dataset. Learn the modern workflow:
   don't train from scratch — adapt what already works.

## Setup

```bash
pip install -r requirements.txt
jupyter notebook
```

Then open the notebooks in order.

## How to follow along

- Run cells top to bottom with **Shift + Enter**
- Read every markdown cell — the explanation lives there
- In interactive cells, move the sliders and watch what changes
- Don't worry about memorizing formulas; the goal is **intuition**

---

*INSEA Innovation Edge · Deep Learning Workshop*
