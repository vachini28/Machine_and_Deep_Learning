<div align="center">

# Machine & Deep Learning — Concepts & Practicals

### A structured collection of Jupyter notebooks covering core ML and DL concepts from scratch

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://tensorflow.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-Latest-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)](https://scikit-learn.org)
[![Kaggle](https://img.shields.io/badge/Datasets-Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com)

</div>

---

## Table of Contents

- [About](#-about)
- [Notebooks Overview](#-notebooks-overview)
- [Topics Covered](#-topics-covered)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Notebook Details](#-notebook-details)

---

## About

This repository is a **personal learning archive** of Machine Learning and Deep Learning concepts implemented as Jupyter notebooks. Each notebook is self-contained and focused on one specific algorithm or technique — covering everything from Python fundamentals all the way up to deep learning architectures like ANN, CNN, and RNN.

> These are not production projects — they are **concept-clearing practicals** built to deeply understand how each algorithm works, when to use it, and how to evaluate it.

---

## Notebooks Overview

```
Machine_and_Deep_Learning/
│
├── Basics.ipynb                         # Python fundamentals for ML
├── EDA and Data Preprocessing.ipynb     # Exploratory Data Analysis
├── Regression.ipynb                     # Linear Regression
├── Naive Bayes & Decision tree.ipynb    # Classification algorithms
├── K-Means.ipynb                        # Clustering
├── ANN.ipynb                            # Artificial Neural Networks
├── CNN.ipynb                            # Convolutional Neural Networks
└── RNN.ipynb                            # Recurrent Neural Networks
```

---

## Topics Covered

| # | Notebook | Topic | Category |
|---|---|---|---|
| 1 | `Basics.ipynb` | Python syntax, data types, list comprehensions, dictionaries | Fundamentals |
| 2 | `EDA and Data Preprocessing.ipynb` | Data loading, missing values, visualisation, feature engineering — Titanic dataset | Data Science |
| 3 | `Regression.ipynb` | Linear Regression — theory, implementation, evaluation metrics (MSE, R²) | Machine Learning |
| 4 | `Naive Bayes & Decision tree.ipynb` | Probabilistic classification, tree-based models, comparison | Machine Learning |
| 5 | `K-Means.ipynb` | Unsupervised clustering, elbow method — Mall Customer Segmentation | Machine Learning |
| 6 | `ANN.ipynb` | Neural network architecture, hidden layers, activation functions — Heart Failure Prediction | Deep Learning |
| 7 | `CNN.ipynb` | Spatial feature extraction, MLP vs CNN comparison — CIFAR-10 image classification | Deep Learning |
| 8 | `RNN.ipynb` | Sequential data, time-series modelling — Malware Detection via API call sequences | Deep Learning |

---

## Tech Stack

| Library | Purpose |
|---|---|
| `numpy` | Numerical computing |
| `pandas` | Data manipulation and analysis |
| `matplotlib` & `seaborn` | Data visualisation |
| `scikit-learn` | ML algorithms, preprocessing, evaluation |
| `tensorflow` / `keras` | Deep learning model building |

---

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab (or use VS Code with the Jupyter extension)

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Machine_and_Deep_Learning.git
cd Machine_and_Deep_Learning
```

### 2. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter
```

### 3. Launch Jupyter

```bash
jupyter notebook
```

Then open any `.ipynb` file from the browser. Each notebook is independent — run them in any order.

---

## Notebook Details

### 1. Basics
Covers core Python constructs needed for data science: list comprehensions, dictionary operations, control flow, and functions. A foundation builder before diving into ML.

### 2. EDA and Data Preprocessing
Uses the **Titanic dataset** to demonstrate the full EDA pipeline — loading data, identifying nulls, visualising distributions, encoding categoricals, and scaling features.

### 3. Regression
Implements **Linear Regression** step-by-step — understanding the cost function, gradient descent intuition, and evaluating model fit using MSE and R² score.

### 4. Naive Bayes & Decision Tree
Compares two popular classification approaches:
- **Naive Bayes** — probabilistic model based on Bayes' theorem
- **Decision Tree** — rule-based splitting with visualisable trees

### 5. K-Means Clustering
Applies **K-Means** unsupervised clustering to the Mall Customer Segmentation dataset. Includes the elbow method for optimal K selection and cluster visualisation.

### 6. ANN — Artificial Neural Networks
Builds a feedforward neural network using **Keras** to predict heart disease from clinical data. Explores how the number of hidden layers and activation functions affect accuracy.

### 7. CNN — Convolutional Neural Networks
Implements a **CNN on CIFAR-10** (10-class image dataset). Compares performance against a plain MLP to demonstrate why convolutions excel at spatial feature extraction.

### 8. RNN — Recurrent Neural Networks
Uses an **RNN to classify malware vs benign software** based on sequences of API calls — a real-world sequential data classification task.

---

## License

This repository is for educational and reference purposes. Feel free to use, fork, and learn from it.

---

<div align="center">
  <p>Built as part of a structured self-study journey through Machine & Deep Learning</p>
</div>
