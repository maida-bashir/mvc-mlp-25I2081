# MVC Project — Multilayer Perceptron

**Roll No:** 25I-2081  
**Course:** Artificial Neural Networks  
**University:** NUCES

## Project Overview
Manual implementation of a Multilayer Perceptron (MLP) from scratch
using only NumPy, trained on the MNIST handwritten digit dataset.

## Architecture
- Input Layer: 784 neurons
- Hidden Layer 1: 128 neurons (Sigmoid)
- Hidden Layer 2: 64 neurons (Sigmoid)
- Output Layer: 10 neurons (Sigmoid)

## Repository Structure
```
mvc-mlp-25I2081/
├── src/         ← Jupyter Notebook (.ipynb)
├── data/        ← mnist.npz dataset
├── report/      ← PDF report (compiled from Overleaf)
└── README.md
```

## How to Run
1. Install dependencies: `pip install numpy matplotlib`
2. Open `src/mvc_mlp_25I2081.ipynb` in Jupyter Notebook
3. Run all cells from top to bottom (Cell 1 → Cell 15)
4. MNIST downloads automatically on first run

## Results
- Training: 20 epochs, batch size 32, learning rate 0.1
- Loss function: Mean Squared Error (MSE)
- Optimizer: Mini-Batch Gradient Descent
