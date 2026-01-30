# Task 10 – Handwritten Digit Classification using KNN

## 📌 Overview
This project implements **K-Nearest Neighbors (KNN)** to classify handwritten digits using the **Scikit-learn Digits dataset**.  
The goal is to understand **distance-based classification** and how accuracy changes with different K values.

---

## 🛠 Tools Used
- Python  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 📊 Dataset
- **Sklearn Digits Dataset**
- Contains 8×8 pixel images of handwritten digits (0–9)

---

## 🚀 Steps Performed
1. Loaded the digits dataset
2. Visualized sample digit images
3. Split data into training and testing sets
4. Applied feature scaling using `StandardScaler`
5. Trained KNN model with K = 3
6. Tested multiple K values (3, 5, 7, 9)
7. Plotted Accuracy vs K graph
8. Generated confusion matrix
9. Displayed test images with predicted labels

---

## 📈 Results
- Best accuracy achieved by tuning K value
- Accuracy vs K graph used to select optimal K
- Confusion matrix shows digit-wise performance

---

## 📁 Deliverables
- Jupyter Notebook
- Accuracy vs K plot
- Confusion Matrix

---

## 🎯 Learning Outcome
- Understanding of KNN algorithm
- Importance of feature scaling
- Effect of K value on model performance

---

## ✅ Conclusion
KNN is a simple and effective algorithm for handwritten digit classification when proper scaling and K tuning are applied.
