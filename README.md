# Wine Quality Prediction with Multilayer Perceptron (MLP)

### A Tutorial on Model Capacity and Performance  
Author: <Your Name> — Student ID: <Your ID>  
Course: Fundamentals of Data Science — 2025

---

## 📌 Project Overview
This project explores how **hidden layer width** affects the performance of a **Multilayer Perceptron (MLP)** neural network for predicting wine quality from physicochemical properties.

The tutorial teaches:
- How to build and train an MLP on tabular data
- Why neural network **capacity** matters
- What happens when a model **underfits** or **overfits**
- How to interpret performance graphs and confusion matrices

The work includes:
✔ A full written tutorial (PDF)  
✔ Executable Jupyter Notebook  
✔ Automatically generated plots (PNG)  
✔ References and ethical discussion  

---


## 🧠 Technique & Focus
We use a **single-hidden-layer MLP (scikit-learn)** with ReLU activation.

### Hidden layer widths tested:
> `8, 16, 32, 64, 128` neurons

For each width we record:
- Training accuracy
- Test accuracy
- Class-wise predictions (confusion matrix)

This reveals the **bias–variance trade-off**:
- Too small → **underfitting**
- Too large → **overfitting**
- Moderate width → **best generalisation**

---

## 🧪 Dataset
WineQT dataset (Vinho Verde wine)  
11 numeric features → 1 multiclass label `quality`  
Example features: acidity, pH, alcohol, sulphates, etc.

The dataset includes **imbalanced classes**, so accuracy alone does not tell the full story.





 
