# Wrapper Feature Selection using Logistic Regression

## 📌 Overview
This project demonstrates the use of wrapper methods for feature selection:
- Recursive Feature Elimination (RFE)
- Forward Selection

## 📊 Dataset
The dataset contains customer attributes including:
- age, income, experience, score, click_rate, time_spent
- noise1, noise2 (irrelevant features)

## ⚙️ Methods Used
- Logistic Regression
- RFE (Backward Selection)
- Forward Selection

## 📈 Results
| Method | Accuracy |
|--------|----------|
| Baseline | 0.872 |
| RFE | 0.755 |
| Forward Selection | (your value) |

## 🔍 Conclusion
- Baseline performed best
- RFE reduced performance due to noise features
- Forward selection improved feature selection

## 🛠️ Tools
- Python
- Pandas
- Scikit-learn
- Matplotlib
