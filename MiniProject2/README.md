# Mini Project 2: Diving Deeper into Machine Learning

## Overview
This repo contains my solutions for **Mini Project 2** of the *Machine Learning (Spring 1403)* course. We really got into some core ML topics here, exploring neural network basics, advanced classification strategies, and the power of ensemble methods.

---

# What I Explored & Learned

## Question 1: Activation Functions & Simple Neural Networks
*   **Activation Functions:** Looked at how Sigmoid and ReLU (and ELU!) act as activation functions in neural networks, especially for binary classification. We compared how they work and their gradients.
    *   *ELU Equation Note:*
        *   ELU(x) = x if x ≥ 0
        *   ELU(x) = α (eˣ - 1) if x < 0
*   **McCulloch-Pitts Neuron:** Built a basic neural network (like a perceptron) to classify a shaded triangle.
    *   Generated about 2000 random points.
    *   Visualized the decision boundaries with two different activation functions.

## Question 2: Fault Detection with MLP
*   **Data Prep:** Worked with the CWRU Bearing dataset, picking out examples of both healthy and faulty states.
*   **Building the MLP:** Trained a Multi-Layer Perceptron (MLP) to classify these states.
    *   Did the usual feature extraction and normalization.
    *   Split the data into training, validation, and testing sets.
    *   Evaluated performance using accuracy, a confusion matrix, and a classification report.
*   **Tweaking Performance:** Experimented with different loss functions and optimizers to see how they affected the model's results.

## Question 3: Trees & Ensembles
*   **Dataset:** Used datasets like forest cover types or drug classification.
*   **Decision Trees:** Built and visualized a decision tree, then checked its accuracy and confusion matrix.
*   **Fine-Tuning Trees:** Analyzed how things like pruning depth affect the tree's performance.
*   **Ensemble Power:** Implemented and compared AdaBoost and Random Forest models, tuning parameters to get better results.

## Question 4: Naive Bayes for Heart Health
*   **Getting Ready:** Used the heart disease dataset, applying normalization and splitting it for training and testing.
*   **Gaussian Naive Bayes:** Trained a Gaussian Naive Bayes classifier.
    *   Evaluated with a confusion matrix.
    *   Compared Micro vs. Macro metrics from the `classification_report`.
*   **Checking Predictions:** Picked 5 random test samples and compared the model's predictions against the actual results.

---

## Tools & Libraries
- Python (mostly in Jupyter Notebooks)
- Scikit-learn (the MVP for most of this!)
- NumPy, Pandas, Matplotlib (for data wrangling and plotting)
- Google Colab (for when things got computationally heavy)
- Public Datasets (Kaggle, CWRU, etc. - good practice finding them!)

---

## Author
**Parisa Ghorbanpour**  
Graduate Student, Machine Learning 2024  
K. N. Toosi University of Technology
