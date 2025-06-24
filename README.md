# Fraud Detection in Banking Data using Hybrid Machine Learning

## 📌 Overview
This project focuses on detecting fraudulent banking transactions using a hybrid approach that combines multiple machine learning and deep learning models. It tackles challenges related to data imbalance and evolving fraud patterns by leveraging advanced algorithms and ensemble techniques.

## 🎯 Objectives
- Detect credit card fraud using robust machine learning models.
- Improve detection accuracy with ensemble methods.
- Handle class imbalance using class weight-tuning.
- Provide a Flask-based user interface for testing and authentication.

## 🧠 Models & Techniques
- **LightGBM**
- **XGBoost**
- **CatBoost**
- **Logistic Regression**
- **Random Forest**
- **Neural Network**
- **Ensemble Models**: Majority Voting & Stacking

## ⚙️ Methodology
1. **Data Preprocessing**: Handling missing values, scaling, and balancing the dataset.
2. **Feature Engineering**: Using PCA and information gain for feature selection.
3. **Model Training**: Training individual models and tuning using Bayesian Optimization.
4. **Evaluation**: Using ROC-AUC, Precision, Recall, F1-Score, and MCC.
5. **Visualization**: Performance comparison using charts and curves.
6. **Deployment**: Simple Flask interface for user testing and predictions.

## 📊 Dataset
- **Source**: Kaggle Credit Card Fraud Detection Dataset
- **Size**: 284,807 transactions
- **Fraudulent Transactions**: ~0.17%

## 🚀 Results
- Ensemble models, especially **Stacking**, outperformed individual models.
- Achieved high scores across multiple evaluation metrics.
- Demonstrated robustness against imbalanced data and fraud variations.

## 🖥️ Front-End
A lightweight **Flask** web interface is included for:
- User authentication
- Inputting transaction data
- Viewing model predictions

## 📌 Conclusion
This project shows that combining optimized ML/DL models significantly boosts fraud detection performance. It provides a scalable and efficient solution for real-world banking data analysis.

## 🛠️ Future Work
- Integrate real-time transaction monitoring
- Explore deeper ensemble techniques
- Improve front-end usability and deployment

---
  

