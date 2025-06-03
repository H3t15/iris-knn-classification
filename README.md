# 🌸 K-Nearest Neighbors (KNN) Classification on the Iris Dataset

This project demonstrates how to implement and evaluate a **K-Nearest Neighbors (KNN)** classifier on the classic [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris). It includes data preprocessing, model evaluation using cross-validation, confusion matrix analysis, and decision boundary visualization.

---

## 📌 Project Flow

This section outlines the end-to-end flow of the KNN classification pipeline:

### 1. 📥 Load Dataset
- Read the `Iris.csv` file using `pandas`.
- Explore the dataset to understand feature and class distributions.

### 2. 🧼 Preprocess Data
- Select features (X) and target (y).
- Normalize features using `StandardScaler` to improve distance-based learning.

### 3. 🤖 Train KNN Classifier
- Use `KNeighborsClassifier` from `sklearn`.
- Train the model on the preprocessed data.

### 4. 🔁 Cross-Validation
- Perform **5-fold cross-validation** for values of `k = 1 to 10`.
- Compute mean accuracy for each value of `k`.

### 5. 🏆 Select Best K
- Identify the `k` value with the highest cross-validation accuracy.
- Train final model using the best `k`.

### 6. 📊 Evaluate Model
- Predict using test data or the full dataset.
- Generate a **confusion matrix**.
- Optionally compute precision, recall, and F1-score.

### 7. 🖼️ Visualize
- Plot **accuracy vs k**.
- Show **confusion matrix heatmap**.
- Visualize **decision boundaries** using two key features (e.g., Petal Length & Width).

---

## ✅ Features

- Load and preprocess the Iris dataset
- Normalize features using `StandardScaler`
- Train and evaluate KNN for different `k`
- Cross-validation (5-fold)
- Confusion matrix
- Decision boundaries visualization

---
