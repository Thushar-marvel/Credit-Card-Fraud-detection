# Credit-card-fraud-detection
Anamoly detection in credit card transactions using different Machine learning algorithms in python
Used supervised learning algolithms -Logistic regression,Decision tree, random forest, bagging, xgbost,KNN and SVM classifiers
Unsupervised learning algorithms- Isolation forest and local outlier Factor

# Steps involved in building model
1.Loading packages
The packages are Pandas to load data and to do data analysis, Numpy to work with arrays, scikit-learn is used for building the model and evaluating it,seaborn  and matplotlib for data visualisation, pydotplus to visualize the decision tree and finally xgboost model

2.Loading data - The dataset used in the project is the Kaggle Credit Card Fraud Detection dataset https://www.kaggle.com/mlg-ulb/creditcardfraud

The dataset consists of 284807 transcation datas with features- 'Time', 'V1', 'V2', 'V3', 'V4', 'V5', 'V6', 'V7', 'V8', 'V9', 'V10',
       'V11', 'V12', 'V13', 'V14', 'V15', 'V16', 'V17', 'V18', 'V19', 'V20',
       'V21', 'V22', 'V23', 'V24', 'V25', 'V26', 'V27', 'V28', 'Amount','Class'
       
3.Data analysis-Exploring the dataset to gain an understanding of the type, quantity, and distribution of data in our dataset. Data analysis is done to check any outliers ,missing values and categorical variables in the dataset. Data visualization is done  using seaborn and matplotlib pacakges

4.Creating training and testing data - Using scikit-learn train-test split function data set is divided 80% as train and 20% as test.

5.Creating model- Using scikit-learn ,  9 different classification models are built.
Logistic regression,Decision tree, random forest, bagging, xgbost,KNN , SVM classifiers,Isolation forest and local outlier Factor

6.Model evaluation- We evaluated our built models using the evaluation metrics provided by the scikit-learn package. The evaluation metrics we are going to use are the accuracy score metric, f1 score metric, and finally the confusion matrix.




  


