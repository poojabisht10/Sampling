# Sampling Techniques on Imbalanced Credit Card Dataset

**Course:** UCS654 – Predictive Analytics using Statistics  
**Assignment:** Sampling  
**Student Name:** Pooja Bisht  
**Roll Number:** 102303845  

---

## 1. Introduction

In real-world machine learning problems, datasets are often imbalanced, where one class heavily dominates the other. This imbalance can significantly degrade model performance, especially when the minority class represents critical outcomes such as fraud detection.

This project focuses on applying and analyzing different **sampling techniques** to handle class imbalance in a **credit card transaction dataset** and evaluating their impact on various machine learning classification models.

---

## 2. Objective

The objectives of this project are:

- To study the effect of class imbalance on classification models  
- To apply different sampling techniques to balance the dataset  
- To evaluate and compare model performance using appropriate metrics  
- To understand why accuracy alone is insufficient for imbalanced datasets  

---

## 3. Dataset Description

- Credit card transaction dataset  
- Binary classification problem: **Fraud vs Non-Fraud**  
- Highly imbalanced class distribution  
- Real-world application: **Fraud Detection and Anomaly Detection**

---

## 4. Sampling Techniques Implemented

The following sampling methods are used to address class imbalance:

1. **Random Under Sampling**  
2. **Random Over Sampling**  
3. **SMOTE (Synthetic Minority Over-sampling Technique)**  

---

## 5. Machine Learning Models Used

The following classifiers are trained and evaluated on the sampled datasets:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)

---

## 6. Evaluation Metrics

To ensure proper evaluation of models on an imbalanced dataset, the following metrics are considered:

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC Score  

---

## 7. Results and Observations

- Class imbalance significantly impacts model predictions.  
- Sampling techniques improve minority class (fraud) detection.  
- Precision, Recall, F1-Score, and ROC-AUC provide better insight than accuracy alone.  
- SMOTE generally improves recall for the minority class.  

---

## 8. Conclusion

This project demonstrates the importance of handling class imbalance in machine learning tasks. Proper sampling techniques combined with suitable evaluation metrics lead to more reliable and meaningful model performance, especially in high-risk applications like fraud detection.

---

## 9. How to Execute the Project

```bash
git clone <repository-url>
cd <repository-name>
pip install -r requirements.txt
python main.py
