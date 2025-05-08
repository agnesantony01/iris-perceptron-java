# Perceptron Algorithm - Iris Flower Classification

This repository contains a simple Java implementation of the **Perceptron algorithm**, a fundamental binary classifier, used here to classify **Iris-setosa** and **Iris-versicolor** from the famous Iris dataset.

## 📌 Project Overview

- **Algorithm**: Perceptron (Binary Classification)
- **Language**: Java
- **Dataset**: Iris Dataset (only Setosa and Versicolor classes)
- **Features Used**: Petal length and petal width
- **Output**: Model predictions for test samples with accuracy

## 🧠 What is a Perceptron?

The Perceptron is a type of linear classifier, and one of the simplest types of artificial neural networks. It attempts to find a linear decision boundary to separate two classes by adjusting weights based on misclassified examples during training.

## 🗂️ Project Structure

Perceptron-project/
├── Perceptron.java          # Core Perceptron implementation
├── PerceptronIris.java      # Main class with training and prediction logic
├── IrisData.txt             # Custom dataset file with feature values and labels
└── README.md                # This file

## 📊 Dataset

The dataset is a simplified version of the Iris dataset containing only two classes:
- Iris-setosa → labeled as `0`
- Iris-versicolor → labeled as `1`

It includes two features:
- Petal length
- Petal width

These values are read from `IrisData.txt`.

## 🚀 How to Run

1. Compile the Java files:
   javac Perceptron.java PerceptronIris.java

2. Run the program:
   java PerceptronIris

3. Expected Output: The model will print the final weights, the number of epochs, and test predictions with accuracy.

## ✅ Sample Output

Final weights: [0.4, -0.6, 0.3]  
Training completed in 8 epochs.  
Prediction on test data: [0, 1, 0, 1]  
Accuracy: 100%

## 📚 References

- Iris Dataset on UCI: https://archive.ics.uci.edu/ml/datasets/iris
- Perceptron Algorithm – Rosenblatt, 1958

## 🛠️ Future Improvements

- Extend to multi-class classification (Iris-virginica)
- Add GUI for visualization
- Integrate evaluation metrics (precision, recall, F1-score)

---

> Developed as a mini project to understand how Perceptron works with real-world datasets using Java.
