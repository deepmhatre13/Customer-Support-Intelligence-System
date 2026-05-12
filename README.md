# Customer Intelligence NLP System

An explainable NLP-based customer support intelligence framework built using TF-IDF and calibrated SVM on a large-scale real-world Twitter customer support dataset (~2.8M interactions).

## Features
- Customer intent classification
- Churn-risk estimation
- Escalation analysis
- Retention recommendation engine
- Explainable NLP analytics

## Final Model Performance

```text
Accuracy Score : 0.9118
Weighted F1    : 0.9109
```

## Dataset
Customer Support on Twitter Dataset:

https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter

## Download Dataset

```bash
pip install kaggle

kaggle datasets download -d thoughtvector/customer-support-on-twitter
```

## Models Used
- Logistic Regression
- Linear SVM
- Calibrated SVM

## Technologies
- Python
- Scikit-learn
- Pandas
- NLP
- TF-IDF

## Repository Structure

```text
customer-intelligence-nlp/
│
├── customer_intelligence_nlp.ipynb
├── calibrated_svm_model.pkl
└── tfidf_vectorizer.pkl
```

## Author
Deepam Mhatre  
Sardar Patel Institute of Technology
