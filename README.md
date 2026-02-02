# From-Single-Models-to-Ensemble-Power
## Overview
This project builds an end-to-end machine learning pipeline to predict whether a customer will subscribe to a term deposit using real-world marketing data. The focus is on data preprocessing, feature engineering, model comparison, and evaluation on imbalanced data.

---

## Dataset
- **Source:** UCI Bank Marketing Dataset  
- **Task:** Binary classification (subscription: yes / no)  
- **Features:** Demographics, contact information, campaign history, and economic indicators  
- **Challenge:** Class imbalance and mixed categorical/numerical features

---

## Methodology
- **Data Cleaning:** handled missing values, encoded categorical variables, scaled numerical features  
- **Feature Engineering:** one-hot encoding, stratified train/test split  
- **Models Trained:**
  - Decision Tree  
  - Random Forest  
  - Gradient Boosting  
  - XGBoost  
- **Evaluation:** accuracy, precision, recall, F1-score (emphasis on recall for the minority class)

---

## Results
- Tree-based ensemble models outperformed single models  
- **Boosted models achieved the best overall performance**, especially on imbalanced data  
- Clear trade-offs observed between interpretability and predictive performance

---

## Tech Stack
`Python · pandas · numpy · scikit-learn · XGBoost · matplotlib · seaborn`
