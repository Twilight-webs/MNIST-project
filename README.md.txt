# MNIST Digit Classifier (PyTorch)

## Overview
This project builds a **handwritten digit classifier (0–9)** using the **MNIST dataset** and **PyTorch**. The model is trained to recognize digits from grayscale images.

---

## Features
- Automatically downloads MNIST dataset  
- Preprocesses images into tensors  
- Trains a neural network model  
- Evaluates test accuracy  
- Displays predictions visually  
- Saves trained model  

---

## Technologies Used
- Python  
- PyTorch  
- Torchvision  
- Matplotlib  

---

## Model Architecture
- Input: 28 × 28 images (flattened to 784)  
- Hidden Layer: 128 neurons + ReLU  
- Dropout: 0.2 (prevents overfitting)  
- Output: 10 classes (digits 0–9)  

---

## How to Run (Google Colab)

1. Open Colab: https://colab.research.google.com  
2. Create a new notebook  
3. Enable GPU:
   - Runtime → Change runtime type → GPU  
4. Paste the code into a cell  
5. Run all cells  

---

## Installation (if running locally)
```bash
pip install torch torchvision matplotlib