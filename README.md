# telco_churn_w_mlops

Data:
- the data can be obtained through the following kaggle link:
    https://www.kaggle.com/datasets/kapturovalexander/customers-churned-in-telecom-services

Data treatment:
- Label encoding: good for tree-based models
- One-Hot encoding: will create even more categorical features

Workflow:
- train-test split
- treating missing data (Total charges)
- categorical encoding (one hot encoding for low-cardinality, target encoding for high-cardinality)
- outliers analysis
- treating outliers
- scaling data
- training model: XGBoost with SHAP
- model evaluation