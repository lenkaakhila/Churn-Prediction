
# 🔄 Customer Churn Prediction

This project analyzes customer behavior to predict whether a customer will churn (i.e., stop doing business with a company). The dataset used is from a **telecom company**, and the goal is to help businesses retain customers by identifying churn risk early.

## 📁 Repository Structure

```
Churn-Prediction/
├── akhila.ipynb          # Main notebook with EDA, modeling, and evaluation
├── churn_data.csv        # Dataset used (if available)
├── README.md             # Project documentation
```

## 📌 Problem Statement

Customer churn is a major concern for subscription-based businesses. By predicting churn, companies can take proactive steps to retain valuable customers. This notebook applies data science techniques to build a predictive model for churn.

## 🔧 Tools & Libraries Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn (for data visualization)
- Scikit-learn (for preprocessing, modeling, evaluation)
- Logistic Regression, Random Forest, Decision Trees, etc.

## 📊 Workflow

1. **Data Loading and Cleaning**
   - Handled missing values
   - Removed duplicates
   - Converted categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Univariate & bivariate visualizations
   - Correlation heatmap
   - Churn rate by contract type, internet service, etc.

3. **Feature Engineering**
   - Label encoding
   - Feature selection and scaling

4. **Model Building**
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
   - XGBoost (if implemented)

5. **Model Evaluation**
   - Confusion Matrix
   - Accuracy, Precision, Recall, F1-score
   - ROC Curve and AUC

