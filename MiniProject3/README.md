# Mini Project 3: SVMs and Dimensionality Reduction

## Overview
This repository contains my work for **Mini Project 3** in the *Machine Learning (Spring 1403)* course. This project was all about getting hands-on with Support Vector Machines (SVMs) and exploring dimensionality reduction techniques like PCA.

---

# What I Explored & Learned

## Data Preprocessing & PCA
*   **Flower Dataset:** Started by preprocessing the classic flower dataset (likely Iris), getting it ready for analysis.
    *   Calculated basic statistics: means for `sepal_length`, `sepal_width`, `petal_length`, `petal_width`.
    *   Computed the variance for each of these features.
*   **Dimensionality Reduction:** Performed Principal Component Analysis (PCA) and visualized the data in three dimensions, helping to see underlying structures.

## Linear SVM
*   Implemented and trained a linear Support Vector Machine.
*   Explored SVM classification specifically in a 2D space, visualizing how it separates data points.

## Polynomial Kernels
*   **Polynomial SVM:** Investigated the effect of using a polynomial kernel for SVM classification.
    *   Trained an SVM with a polynomial kernel, specifically experimenting with `degree=10` to see how a higher-degree polynomial boundary behaves.

## SVM From Scratch
*   **Building SVM:** Took on the challenge of implementing an SVM **completely from scratch**!
    *   Used the `CVXOP` library to solve the quadratic dual problem, which is a standard and efficient way to train SVMs.
    *   For multiclass classification, I implemented the **one-vs-all** strategy, training a separate SVM for each class.

---

## Tools & Libraries
- Python
- Scikit-learn (for PCA, linear/kernel SVMs, and comparison)
- NumPy, Pandas (for data handling and stats)
- Matplotlib (for visualizations)
- CVXOP (for solving the SVM dual problem from scratch)

---

## Author
**Parisa Ghorbanpour**  
Graduate Student, Machine Learning 2024  
K. N. Toosi University of Technology

