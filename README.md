# Boosting Techniques Assignment

## 📌 Overview
This repository contains implementations of various **Boosting techniques** used in **Machine Learning**. It covers multiple algorithms like **AdaBoost, Gradient Boosting, XGBoost, LightGBM, and CatBoost** with practical examples and evaluations.

## 🚀 Implemented Techniques

### 1️⃣ **AdaBoost**
- Train an **AdaBoost Classifier** on a sample dataset and print model accuracy.
- Train an **AdaBoost Regressor** and evaluate using **Mean Absolute Error (MAE)**.
- Analyze the effect of **different learning rates** on AdaBoost performance.
- Visualize **feature importance** using AdaBoost.

### 2️⃣ **Gradient Boosting**
- Train a **Gradient Boosting Classifier** on the **Breast Cancer dataset** and print feature importance.
- Train a **Gradient Boosting Regressor** and evaluate using **R-Squared Score**.
- Plot **learning curves** to analyze model performance.
- Visualize the **ROC curve** for Gradient Boosting Classifier.

### 3️⃣ **XGBoost**
- Train an **XGBoost Classifier** and compare accuracy with Gradient Boosting.
- Train an **XGBoost Regressor** and evaluate using **Mean Squared Error (MSE)**.
- Tune the **learning rate** using **GridSearchCV**.
- Train an **XGBoost Classifier** for **multi-class classification** and evaluate using **log-loss**.

### 4️⃣ **CatBoost**
- Train a **CatBoost Classifier** and evaluate using **F1-Score**.
- Train a **CatBoost Classifier** on an **imbalanced dataset** and compare performance **with and without class weighting**.
- Plot the **confusion matrix** for a CatBoost model.

## 📂 Structure
```
📁 boosting-techniques-assignment
│── 📄 README.md (This file)
│── 📄 adaboost_classifier.py
│── 📄 adaboost_regressor.py
│── 📄 gradient_boosting_classifier.py
│── 📄 gradient_boosting_regressor.py
│── 📄 xgboost_classifier.py
│── 📄 xgboost_regressor.py
│── 📄 catboost_classifier.py
│── 📄 catboost_imbalanced.py
│── 📄 utils.py (Helper functions)
└── 📂 datasets (Custom datasets if needed)
```

## 🛠 Installation
To run the code, install the required dependencies using:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn xgboost catboost lightgbm
```

## 📊 Results & Analysis
- **Comparisons** between different boosting techniques.
- **Feature importance** visualizations.
- **Performance metrics** (Accuracy, Log-Loss, F1-Score, ROC Curves, etc.).

## 🤖 Future Enhancements
- Implement **LightGBM** examples.
- Perform **hyperparameter tuning** for all models.
- Explore **Stacked Boosting** for better performance.

## 💡 Contributing
Feel free to contribute by improving code, adding new boosting techniques, or optimizing hyperparameters. Fork this repo and submit a **Pull Request**!

## 📜 License
This project is licensed under the **MIT License**.

---
📢 **Follow & Star** ⭐ the repository if you find it helpful!

