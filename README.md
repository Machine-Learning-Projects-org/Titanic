# 🚢 Titanic Survival Prediction - ML Beginner Project

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit-learn-1.0+-orange.svg)](https://scikit-learn.org/)

## 📋 **Problem Statement**
**Predict whether Titanic passengers survived based on demographic and ticket data using KNN and Logistic Regression classifiers.**

## 📊 **Dataset**
- **Source**: [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data)
- **Training**: 891 passengers
- **Test**: 418 passengers  
- **Features**: Pclass, Age, Sex*, Parch, SibSp, Fare (*one-hot encoded)

## 🧹 **Data Preprocessing**
- ✅ Missing Age → Mean imputation
- ✅ Missing Fare → Drop rows  
- ✅ Sex → Dummy encoding (male=1, female=0)
- ✅ Name column dropped

## 🤖 **Models Implemented**

| Model | Test Predictions |
|-------|------------------|
| KNN (k=5) | **154 survivors** |
| Logistic Regression |  **155 survivors** |

**KNN k-tuning results:**
