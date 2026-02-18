# 💳 Credit Card Fraud Detection using Logistic Regression

## 📌 Overview

This project focuses on detecting fraudulent credit card transactions using **Logistic Regression**, a supervised machine learning algorithm.
The goal is to classify transactions as **fraudulent or legitimate** based on transaction features.

Fraud detection is a real-world problem used by banks and financial institutions to prevent financial losses.

---

## 🎯 Objectives

* Build a binary classification model
* Detect fraudulent transactions
* Handle imbalanced datasets
* Evaluate model performance using appropriate metrics

---

## 📊 Dataset

This project uses the **Credit Card Fraud Detection Dataset** from Kaggle.

### Dataset Features:

* 284,807 transactions
* 30 features
* PCA-transformed variables (V1–V28)
* `Amount` and `Time` features
* `Class` column:

  * 0 → Normal transaction
  * 1 → Fraud transaction

---

## ⚠️ Challenges

### 1. Imbalanced Dataset

Fraud cases are extremely rare:

* Normal transactions ≈ 99.8%
* Fraud transactions ≈ 0.2%

This makes accuracy misleading, so we focus on:

* Precision
* Recall
* F1-score

---

## 🧠 Algorithm Used

### Logistic Regression

Logistic regression is a statistical model used for binary classification.

### Mathematical Formula:

Sigmoid function:

P(y = 1 | x) = 1 / (1 + e^-(wᵀx + b))

Where:

* w = weights
* x = input features
* b = bias

If probability > threshold → Fraud

---

## 🔄 Workflow

1. Import libraries
2. Load dataset
3. Data preprocessing
4. Handle class imbalance
5. Train-test split
6. Train Logistic Regression model
7. Evaluate performance
8. Visualize results

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 📈 Model Evaluation

Since the dataset is imbalanced, we evaluate using:

* Precision → Correct fraud predictions
* Recall → Ability to detect fraud
* F1-score → Balance of precision and recall
* Confusion Matrix

---

## 📊 Results

The model successfully detects fraudulent transactions with high recall and reasonable precision.

Logistic regression provides:

* Fast training
* Interpretable results
* Good baseline performance

---

## 🚀 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Apply SMOTE for balancing
* Hyperparameter tuning
* Deep learning approaches
* Real-time fraud detection systems

---

## 📌 Applications

* Banking fraud detection
* Online payment security
* Financial risk analysis
* E-commerce platforms

---

## 🧾 Conclusion

This project demonstrates how logistic regression can be used as a baseline model for fraud detection.
Despite its simplicity, it performs well and provides interpretable results, making it a strong starting point for real-world fraud detection systems.

---

## 👨‍💻 Author

B.karthikeya
Computer Science Engineering Student
Interested in Machine Learning & Real-World Problem Solving


---

## ⭐ If you like this project

Give it a star ⭐ on GitHub!

