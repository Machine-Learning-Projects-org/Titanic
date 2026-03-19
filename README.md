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
k=1: 97.8% (overfit)
k=5: 81.1% (optimal)
k=10: 76.7% (underfit)


## 📁 **Files**
├── train.csv # Training data (891 records)
├── test.csv # Test data (418 records)
├── Titanic.ipynb # Complete analysis & predictions
└── README.md # This file


## 🚀 **How to Run**
```bash
# 1. Clone repo
git clone <your-repo-url>
cd Titanic-Survival-Prediction

# 2. Install dependencies
pip install pandas scikit-learn matplotlib

# 3. Run notebook
jupyter notebook Titanic.ipynb
```

📈 Key Learnings
KNN hyperparameter tuning (k=1-10)

Handling missing categorical/numerical data

Dummy encoding for classification

Model comparison without test labels

Real-world data preprocessing pipeline

👥 Author
Nihal Pujari
LinkedIn | Data Science Student

📄 License
MIT License - free to use for learning/portfolio

