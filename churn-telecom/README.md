# Data

Telecom operator provides two main types of services:
- landline telephone communication
- internet

Various additional services and several payment/receipt options are available.

The initial data is presented in four separate datasets, which contain information about:
- contracts
- personal clients data
- provided internet services
- provided telephony services

# Task 

To build a prototype of a machine learning model to predict the churn of telecom operator customers.
To train a model which AUC-ROC quality metric will be higher than 0.88

# Main stages  

1. Exploring general project information 
2. Data preprocessing
3. Exploratory data analysis with visualization
4. Data preparation and variable encoding
5. Training and quality evaluation of models
6. Analysis and comparison of the best models

# Used libraries

- Pandas
- Matplotlib
- Seaborn
- Numpy
- Sklearn
  - GridSearchCV
  - roc_auc_score
  - confusion_matrix
  - shuffle
  - train_test_split
  - DecisionTreeClassifier
  - RandomForestClassifier
  - LogisticRegression
- Gradient boosting
  - Catboost
  - Lightgbm

