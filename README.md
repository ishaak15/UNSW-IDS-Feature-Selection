### UNSW-IDS-Feature-Selection

###### In this work, we apply a two-stage anomaly-based network intrusion detection process using the UNSW-NB15 dataset. In stage 1 we make of three different Feature Selection Algorithms to rank the features in the Dataset according to their relation to the resulting labels. We plan to make use of Recursive Feature Elimination, Pearson Correlation and ExtraTreesClassifier which use inbuilt class feature_importances of tree-based classifiers we also plot graphs of feature importances for better visualization among other techniques to select the best dataset features for the purpose of machine learning.

###### After ranking the features we will be making 2 new Datasets consisting of the top 15 and 30 features based on the average of the ranks obtained by the features from the 3 ranking algorithms and use them alongside the original dataset with all the features. 

###### Then we perform a classification activity in order to identify intrusive traffic from a normal one, using a number of Machine Learning techniques, including k Nearest Neighbour, Logistic Regression Classifier, Decision Tree, Random Forest, Neural Network and a few ensemble classifiers.

###### The result of the classification activity will make of certain performance metrics which include, accuracy, precision, recall, and f1 measure. With the results of the Machine Learning models, we can understand the necessity of feature selection and also all the data packet attributes that can be monitored by firewalls.

#### About the files:

##### UNSW_IDS_analysis.ipynb:
###### This file houses all initial analysis data of the Dataset. Followed by thorough cleaning, label encoding, and removal of duplicates. All this is followed by 3 Feature selection Algorithms, to pick the top 15, 30, and finally all features from the Dataset. The completed files were then exported to our Google Drive and later moved here in the form of the following files

##### Training Dataset Files:
      Dataset1.csv
      Dataset2.csv
      Dataset3.csv
      
##### Testing Dataset Files:
      Testset1.csv
      Testset2.csv
      Testset3.csv
      
##### Training_and_Testing.ipynb:
###### This file has all the models, and their training and testing results. A total of 8 ML Algorithms were implemented to compare and contrast the effect of feature selection on the different metrics for strengthening Intrusion Detection Systems. The following models were used:
      k Nearest Neighbour
      Decision Tree
      Multinomial Naive Bayes
      Random Forest
      Logistic Regression Classifier 
      Neural Network
      Ensemble Classifier: AdaBoost Classifier using Decision Tree
      Ensemble Classifier: Stack Classifier of KNN, Random Forest and XGBoost
      
      
