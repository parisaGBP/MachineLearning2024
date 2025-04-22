# Mini Project 2 - Learning Objectives

## Overview
This repository contains solutions to **Mini Project 2** of the *Machine Learning (Spring 1403)* course. It focuses on advanced machine learning concepts including neural networks, classification techniques, evaluation metrics, and tree-based models.

---

## What You'll Learn

### Question 1: Activation Functions and Neural Networks
1. **Activation Functions**: Analyze a binary classification problem using either a Sigmoid or ReLU activation function in the final network layer. Discuss their behaviors and compare gradients.  
   - **ELU Equation**:  
     - ELU(x) = x if x ≥ 0  
     - ELU(x) = α (eˣ - 1) if x < 0

2. **McCulloch-Pitts Neuron**:  
   Design a simple neural network using a McCulloch-Pitts or perceptron model to classify a shaded triangular region.  
   - Generate 2000 random points.  
   - Use two different activation functions.  
   - Visualize and analyze decision boundaries.

---

### Question 2: Fault Detection with MLP
1. **Data Processing**:  
   Use the CWRU Bearing dataset. Select and describe faulty and healthy data samples.

2. **Modeling**:  
   Train a Multi-Layer Perceptron (MLP) model for classification.  
   - Feature extraction and normalization  
   - Splitting into train/validation/test sets  
   - Evaluation using accuracy, confusion matrix, and classification report

3. **Comparison**:  
   Test different loss functions and optimizers. Analyze their effects on model performance.

---

### Question 3: Decision Trees and Ensemble Methods
1. **Dataset Selection**:  
   Use datasets like forest cover types or drug classification.

2. **Decision Tree Modeling**:  
   Train and visualize a decision tree. Evaluate using confusion matrix and accuracy.

3. **Pruning and Hyperparameters**:  
   Analyze the impact of pruning depth and other tree parameters.

4. **Ensemble Methods**:  
   Implement and compare AdaBoost and Random Forest models. Improve results with parameter tuning.

---

### Question 4: Naive Bayes for Heart Disease Prediction
1. **Preprocessing**:  
   Use the heart disease dataset. Apply normalization and train-test splitting.

2. **Model Training**:  
   Train a Gaussian Naive Bayes classifier.  
   - Evaluate using confusion matrix  
   - Compare **Micro** vs **Macro** metrics using `classification_report`

3. **Prediction Comparison**:  
   Randomly select 5 test samples. Compare model predictions with ground truth.

---

## Tools & Libraries
- Python (Jupyter Notebook)
- Scikit-learn
- NumPy, Pandas, Matplotlib
- Google Colab
- Public Datasets (Kaggle, CWRU)

---

## Author
**Parisa Ghorbanpour**  
Graduate Student, Machine Learning 2024  
K. N. Toosi University of Technology
