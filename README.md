# 📚 Machine Learning Coursework & Case Studies

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-1.3%2B-F7931E.svg?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Course](https://img.shields.io/badge/Course-CSA--64%20Machine%20Learning-purple.svg)](https://github.com/SLAYWITHME2005/Machine-Learning-Assignments-CSA-64)

Curated laboratory assignments, regression modeling, decision tree classifiers, and the capstone group case study for the **Machine Learning (CSA-64)** curriculum.

---

## 🗂️ Curriculum Modules

```plaintext
Machine-Learning-Assignments-CSA-64/
├── Assignment-01-Regression/
│   └── Assignment_01_Regression_Diabetes.ipynb   # Linear & Regularized Regression on Diabetes dataset
├── Assignment-02-Decision-Tree/
│   └── Assignment_02_Decision_Tree_Wine.ipynb    # Multi-class Decision Tree Classifier on Wine dataset
├── Case-Study-Face-vs-Non-Face/
│   ├── Face_Detection_Group_Case_Study.ipynb     # Capstone Case Study: Face vs. Non-Face Classifier
│   ├── test_photo.jpg                            # Evaluation test image
│   └── outputs/                                  # Plots, ROC curves, confusion matrices, metrics CSV
└── README.md
```

---

## 🔬 Module Details

### 1. [Assignment 01: Regression Analysis](Assignment-01-Regression/)
- **Dataset:** Scikit-Learn Diabetes Dataset (442 samples, 10 physiological features).
- **Core Topics:**
  - Exploratory Data Analysis (EDA) and correlation matrix heatmap analysis.
  - Ordinary Least Squares (OLS) Linear Regression vs. Ridge ($\ell_2$) and Lasso ($\ell_1$) regularization.
  - Evaluation metrics: Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and $R^2$ score.
  - Residual diagnostics and feature coefficient interpretation.

### 2. [Assignment 02: Decision Tree Classification](Assignment-02-Decision-Tree/)
- **Dataset:** UCI Wine Recognition Dataset (178 samples, 13 chemical constituents, 3 cultivar classes).
- **Core Topics:**
  - Information gain criteria: Gini Impurity vs. Shannon Entropy.
  - Pre-pruning strategies: `max_depth`, `min_samples_split`, and `min_samples_leaf` to prevent tree overfitting.
  - Multi-class classification report, precision/recall per cultivar, and Confusion Matrix visualization.
  - Decision boundary rendering and tree graph export (`plot_tree`).

### 3. [Capstone Case Study: Face vs. Non-Face Classifier](Case-Study-Face-vs-Non-Face/)
- **Core Objective:** Evaluate and analyze the impact of ensemble learning on classification performance, overfitting dynamics, and out-of-sample generalization.
- **Dataset:** Balanced dataset of 800 images ($64 \times 64$ grayscale: 400 faces, 400 non-face background scenes).
- **Key Tasks:**
  1. Spatial normalization, min-max intensity scaling, and data auditing.
  2. Principal Component Analysis (**PCA Eigenfaces**, 50 orthogonal components).
  3. Single greedy Decision Tree vs. **Random Forest Ensemble** (100 estimators).
  4. Train/test generalization gap analysis and tree depth tuning curves.
  5. Multi-scale sliding window detector with Non-Maximum Suppression (NMS).
- **Results:**
  - Single Decision Tree (PCA): **96.88%** test accuracy (ROC-AUC: 0.969).
  - Random Forest Ensemble (PCA): **99.38%** test accuracy (ROC-AUC: **0.9997**).

---

## 🚀 Environment Setup

```bash
# Clone the repository
git clone https://github.com/SLAYWITHME2005/Machine-Learning-Assignments-CSA-64.git
cd Machine-Learning-Assignments-CSA-64

# Create and activate virtual environment
python -m venv venv
# On Windows:
venv\Scripts\activate

# Install required packages
pip install numpy pandas scikit-learn matplotlib seaborn opencv-python jupyter

# Launch Jupyter Notebook
jupyter notebook
```

---

## 👩‍💻 Author
- **Gayathri Rajeev** ([@SLAYWITHME2005](https://github.com/SLAYWITHME2005))
- B.Tech in Computer Science & Engineering
