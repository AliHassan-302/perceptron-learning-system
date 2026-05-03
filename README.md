# perceptron-learning-system
A Python implementation of a Single-Layer Perceptron built from scratch for binary classification. The model supports training with user-defined datasets, learning rate, and epochs, and demonstrates supervised learning with weight updates and predictions.
# Single Layer Perceptron from Scratch

## 📌 Overview
This project implements a Single-Layer Perceptron from scratch using Python and NumPy. It demonstrates how a basic machine learning model learns binary classification through supervised learning.

---

## 🎯 Objective
- Train a perceptron model on user-defined dataset
- Perform binary classification (0 or 1)
- Update weights using learning rule
- Predict unseen data

---

## ⚙️ How It Works
The model computes:

y = activation(w·x + b)

Where:
- w = weights  
- x = input features  
- b = bias  

Activation function:
- If value ≥ 0 → 1  
- Else → 0  

---

## 🧠 Learning Rule
w = w + learning_rate × (actual - predicted) × x

---

## 🛠️ Technologies Used
- Python
- NumPy

---

## 🚀 How to Run

```bash
python perceptron.py
