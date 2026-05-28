# Mini Project 1 - Learning Objectives

## Overview
This repository contains the complete solutions for **Mini Project 1** of the *Machine Learning (Spring 1403)* course at K. N. Toosi University of Technology.  
The project focuses on linear classifiers, feature engineering, and supervised learning evaluation using both classical and custom implementations.

---
# What I Explored & Learned
#Classifiers: Building and understanding linear classifiers (both for two classes and many) and seeing how they draw decision lines.
#Data: Playing with generated datasets and visualizing them. Also experimented with drawing my own data points.
#Features: Extracting key info from signals (like vibrations) to help models learn better.
#Building Models: Coding models from scratch and then comparing them to ones built with handy libraries like Scikit-learn.
#Regression: Trying out different ways to predict values using weather data (LS, RLS, WLS).

# Project Breakdown

### Question 1: Classifiers & Making Data 
1. Drew diagrams for how classifiers learn and how to make them handle more than two classes.
2. Generated a synthetic dataset (3 features, 4 classes) with `sklearn` and visualized it, noting why it might be tough to classify.
3. Trained a couple of linear models using `sklearn`, tweaking settings like learning rate and epochs.
4. Plotted the decision boundaries and pointed out the mistakes the models made.
5. Tried generating and classifying data using the `drawdata` tool.

### Question 2: Vibes & Features 
1. Explored and downloaded data from the CWRU Bearing Dataset.
2. Chunked up the vibration signals into segments and prepped them for training.
3. Pulled out 8+ important features (like RMS, skewness, etc.) from each vibration chunk.
4. Cleaned up the features (normalization) and talked about why shuffling data is a big deal.


###  Question 3: Weather Predictions 
1. Dug into the Szeged Weather Dataset, looking at temperature, humidity, and apparent temperature correlations and distributions.
2. Implemented Least Squares (LS), Recursive Least Squares (RLS), and Weighted
3. Least Squares (WLS) for regression, comparing their errors.
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
