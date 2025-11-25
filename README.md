# Customer Churn Prediction – Final Report

This repository contains the complete workflow for predicting **customer churn**, including EDA, feature engineering, model training, cross-validation, and performance comparison using Logistic Regression (L1), Decision Trees (C4.5 style), Random Forest, and Gradient Boosting.

---

## 📊 Final Model Performance Comparison

| Model                         | Accuracy | Precision | Recall  |
|------------------------------|----------|-----------|---------|
| L1 Logistic Regression       | 0.8176   | 0.5247    | 0.8183  |
| Decision Tree (C4.5-style)  | 0.7761   | 0.4685    | 0.6090  |
| Random Forest                | 0.8631   | 0.7461    | 0.5436  |
| Gradient Boosting Machine   | 0.8255   | 0.5626    | 0.7020  |

---

## 📝 Conclusion  
Each model presented different strengths. Logistic Regression achieved the **highest recall**, making it the best at identifying churners. The Decision Tree performed moderately but was weaker than the ensemble models. Random Forest obtained the **best accuracy and precision**, making it the strongest overall classifier, though with lower recall. Gradient Boosting provided a balanced performance with strong accuracy and higher recall than Random Forest. In summary, if identifying churners is the top priority, Logistic Regression is the best choice; if overall stability is preferred, Random Forest performs better.

---

## 🚀 Quick Start

```bash
python -m venv venv
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
.env\Scriptsctivate
pip install -r requirements.txt
python -m ipykernel install --user --name=venv --display-name "Python (venv)"
jupyter notebook
```

