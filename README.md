# 🌸 Iris Dataset Classification using SVM

This project demonstrates how to classify the Iris flower dataset using Support Vector Machines (SVM) with scikit-learn. It includes steps for loading the dataset, performing data exploration with visualization, plotting SVM decision boundaries, training the model, and tuning hyperparameters like `gamma`, `C`, and `kernel`.

---

## 📦 Requirements

- Python 3.x
- scikit-learn
- matplotlib
- numpy
- pandas

You can install the required packages using:


pip install scikit-learn matplotlib numpy pandas

## 📊 Project Structure
# Dataset Loading

Load the Iris dataset from sklearn.datasets.

# Data Exploration

Explore the dataset using summary statistics and visualizations.

Use scatter plots to visualize class separation.

Plot decision boundaries of SVM on a 2D projection of features.

# Model Training

Train an SVC (Support Vector Classifier) with a chosen kernel, C, and gamma.

# Hyperparameter Tuning

Use GridSearchCV to find the best parameters from a search space of:

Kernels: 'linear', 'rbf', 'poly', 'sigmoid'

Gamma: [1, 0.1, 0.01, 0.001]

C: [0.1, 1, 10, 100]

## 🧠 Concepts Covered
1. Support Vector Machines (SVM)

2. Feature scaling and selection

3. Data visualization

4. Hyperparameter tuning with GridSearchCV

5. Multiclass classification on the Iris dataset

## 📚 References
Scikit-learn documentation

Iris dataset
