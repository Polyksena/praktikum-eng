# Data

The data is presented in three datasets: source data, training and test sample. It is known that the data is incomplete, and some of the parameters are unavailable.

The columns contain the values of ore parameters at various stages of its processing, indexed by date and time. The dataset with the initial data and the training sample contains target features: efficiency coefficients of ore enrichment at different stages.  

# Task

Development of a model predicting the recovery rate of gold from gold ore

It is necessary to build a machine learning model for an industrial company that develops solutions for the efficient operation of industrial enterprises. The model should predict the recovery coefficient of gold from gold-bearing ore based on data with extraction and purification parameters. 
The model will help optimize production so as not to launch an enterprise with unprofitable characteristics.

# Main stages  

1. Data preparation (including verification of ore recovery efficiency calculation and analysis of features not available in the test set)
2. Data preprocessing
3. Data analysis and visualization
4. Creating a quality metric evaluation function
5. Model training
6. Output

# Used libraries 

- Pandas
- Matplotlib
- Seaborn
- Numpy
- Sklearn
  - DummyRegressor
  - Pipeline
  - GridSearchCV
  - DummyRegressor
  - DecisionTreeRegressor
  - RandomForestRegressor
  - LinearRegression
