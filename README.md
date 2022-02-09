# XGBoost-Classifier-for-TELCO-Churn
XGBoost Classifier implemented for Telco Churn Dataset


In order to run all the notebook's cells you will need to download the main dataset from kaggle. The link is given below

# https://www.kaggle.com/blastchar/telco-customer-churn

The notebook include a tunning procces, employing GridSearchCV in order to find the best parameters for the classification.

In this case, the best performance and accuracy were obtained with:

{'gamma': 0.25,
 'learning_rate': 0.1,
 'max_depth': 3,
 'n_estimators': 100,
 'reg_lambda': 0,
 'scale_post_weight': 1}
