# Mini Project 1 - Learning Objectives

## Overview
This repository contains the complete solutions for **Mini Project 1** of the *Machine Learning (Spring 1403)* course at K. N. Toosi University of Technology.  
The project focuses on linear classifiers, feature engineering, and supervised learning evaluation using both classical and custom implementations.

---

## What You'll Learn

### Question 1: Linear Classification & Dataset Generation
1. **Process Diagram**:  
   Draw a block diagram for the training and evaluation of a binary linear classifier.  
   Also explain what changes are needed to adapt the model to multi-class classification.

2. **Custom Dataset**:  
   Use `sklearn.datasets` to generate a synthetic dataset with 3 features and 4 classes.  
   - Analyze why the dataset might be challenging for classification.  
   - Visualize the generated data.

3. **Model Training with Scikit-learn**:  
   Use at least two linear models from `sklearn.linear_model`.  
   - Tune hyperparameters such as `learning_rate` and `n_epochs`  
   - Compare accuracy and training behavior across classes

4. **Decision Boundary & Misclassification**:  
   Plot decision regions of your trained models.  
   - Highlight misclassified points using distinct colors and shapes.

5. **Custom Data with Drawdata**:  
   Generate a dataset using the `drawdata` tool and repeat training, evaluation, and visualization.

---

### Question 2: Feature Extraction from Vibration Signals
1. **CWRU Dataset Exploration**:  
   Analyze and download fault and normal condition files from the [CWRU Bearing Dataset](https://engineering.case.edu/bearingdatacenter/).

2. **Dataset Formation**:  
   - Segment signals using a sliding window (e.g., 100 samples per segment, 200 total).
   - Label and format into a classification-ready dataset.

3. **Feature Extraction**:  
   Extract at least 8 features from each segment using formulas like RMS, skewness, kurtosis, etc.

4. **Preprocessing and Shuffling**:  
   Normalize features using at least two methods.  
   Explain the importance of data shuffling and train/test splitting.

5. **Manual Training Implementation**:  
   Train a model **without using Scikit-learn**.  
   - Plot loss curve  
   - Evaluate performance on test data  
   - Explain if the model is reliable based on the loss shape

6. **Training Using Scikit-learn**:  
   Train a linear classifier with built-in tools.  
   - Compare its performance and plots with the manual method

7. **Exploration with Orange Tool (Optional)**:  
   Explore the use of Orange data mining software to implement logistic regression.  
   - Demonstrate functionality with a screenshot or short video

---

### Question 3: Weather Dataset Regression
1. **Data Analysis**:  
   Use the [Szeged Weather Dataset](https://www.kaggle.com/datasets/budincsevity/szeged-weather/data).  
   - Analyze correlations and histograms for `Temperature`, `Humidity`, and `Apparent Temperature`

2. **Modeling with LS & RLS**:  
   - Implement Least Squares (LS) and Recursive Least Squares (RLS) for regression  
   - Plot errors and compare models

3. **Weighted Least Squares (WLS)**:  
   Explain and apply WLS on the dataset.  
   - Compare with previous models

4. **QR-Decomposition Based RLS (Optional)**:  
   Investigate and optionally implement QR-based RLS.  
   - Bonus question with additional grade

---

## Tools & Libraries
- Python (Jupyter Notebook)
- Scikit-learn
- NumPy, Pandas, Matplotlib
- Orange Data Mining (Optional)
- Google Colab
- Custom Dataset Tools (e.g., `drawdata`, `gdown`)

---

## Author
**Parisa Ghorbanpour**  
Graduate Student, Machine Learning 2024  
K. N. Toosi University of Technology
