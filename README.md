# Support-Vector-Machine
# 🛡️ Classification with Support Vector Machines (SVM)

This repository demonstrates the implementation of **Support Vector Machines (SVM)**, a robust classification algorithm that works by finding the optimal boundary (hyperplane) that maximizes the distance between different classes.

---

## 🛠️ The Machine Learning Stack
* **Python**: Core programming.
* **Pandas & NumPy**: For data manipulation and feature engineering.
* **Scikit-Learn**: For the `SVC` (Support Vector Classification) model and performance tuning.
* **Matplotlib & Seaborn**: For visualizing decision boundaries and margins.

---

## 🧠 Key Concepts Implemented

### 1. The Hyperplane & Margins
Unlike other algorithms that just find any line to separate data, SVM looks for the **Maximum Margin Hyperplane**:
* **Support Vectors:** The data points closest to the boundary that "support" the hyperplane.
* **Margin:** The gap between the support vectors of different classes. SVM aims to make this gap as wide as possible.

### 2. Kernel Trick
Demonstrated how SVM can handle non-linear data by projecting it into higher dimensions:
* **Linear Kernel:** For data that can be separated by a straight line.
* **RBF (Radial Basis Function):** For complex, circular, or overlapping data patterns.

### 3. Hyperparameter Tuning
Explored the impact of key parameters on model performance:
* **C (Regularization):** Balancing the trade-off between a smooth boundary and classifying training points correctly.
* **Gamma:** Defining how far the influence of a single training example reaches.

---

## 📊 Why use SVM?
SVM is highly effective in high-dimensional spaces and is commonly used for:
* **Image Recognition:** Face detection and handwriting recognition.
* **Bioinformatics:** Protein fold and remote homology detection.
* **Text Categorization:** Sorting documents into specific topics.

---

## 🚀 How to Run

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/Manaswi9123/Python-DataScience-Fundamentals.git](https://github.com/Manaswi9123/Python-DataScience-Fundamentals.git)
