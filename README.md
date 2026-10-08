This project develops a machine-learning pipeline to identify e-commerce customers who are at high risk of churning. The objective is to support targeted retention strategies, improve customer relationships, and help allocate marketing resources more effectively.
The analysis considers customer characteristics and purchasing behaviour such as tenure, distance from the warehouse, order activity, complaints, cashback, preferred product category, and marital status.

Methodology

- Exploratory analysis of customer behaviour, churn distribution, correlations, missing values, and outliers.
- Imputation of missing numerical and categorical data.
- Scaling of numerical features and encoding of categorical variables.
- Train-test splitting and class balancing with SMOTE.
- Comparison of XGBoost, CatBoost, Random Forest, and Logistic Regression.
- Hyperparameter optimization using grid search and cross-validation.
- Model comparison through classification metrics, ROC curves, and confusion matrices.
- Analysis of feature importance to identify relevant churn drivers.
- Demonstration of the prediction pipeline on a new hypothetical customer.
