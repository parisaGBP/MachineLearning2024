# MiniProject2 - Machine Learning 2024

This folder contains solutions to the four main questions of Mini Project 2 from the "Machine Learning (Spring 1403)" course at K. N. Toosi University of Technology.

Each notebook includes full code implementations, detailed explanations, and result analysis, following the project requirements. The work is divided into four main sections, each corresponding to a specific question from the project document.

---

## 📁 Files

- `ML_miniproject2_Q1.ipynb`  
  Implementation and analysis of classification using ReLU and sigmoid activation functions. Includes:
  - Gradient comparison
  - ELU activation implementation
  - McCulloch-Pitts and Perceptron modeling to classify a triangle region in 2D

- `ML_miniproject2_Q2.ipynb`  
  Fault diagnosis using the CWRU bearing dataset. Includes:
  - Preprocessing and feature extraction
  - Building an MLP classifier
  - Evaluation using accuracy, confusion matrix, and `classification_report`
  - Comparison of optimizer and loss function effects

- `ML_miniproject2_Q3.ipynb`  
  Decision tree modeling on forest cover type and drug datasets. Includes:
  - Train/test splitting and analysis of overfitting
  - Hyperparameter tuning and pruning effects
  - Random Forest and AdaBoost classifiers
  - Final comparison and performance improvement strategies

- `ML_miniproject2_Q4.ipynb`  
  Naive Bayes classification on a heart disease dataset. Includes:
  - Preprocessing and dataset splitting
  - Comparison of Micro vs. Macro F1-score
  - Detailed confusion matrix analysis
  - Random prediction comparisons

---

## 🔗 References and Datasets

- [CWRU Bearing Dataset](https://engineering.case.edu/bearingdatacenter/download-data-file)
- [Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- [Drugs A/B/C/X/Y Dataset](https://www.kaggle.com/datasets/pablomgomez21/drugs-a-b-c-x-y-for-decision-trees)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)

---

📌 **Note**: All notebooks are configured to be executable in Google Colab. The code uses fixed `random_state` values based on the last two digits of the student ID to ensure reproducibility.

