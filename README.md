# Basic-Projects

I. 2020A2PS1777P_Decision_Tree
   
      Dataset used: spambase_data.csv

      Q1) Creating a decision stump and finding the majority class and error.

      Q2) Creating a decision tree classifier using entropy to measure the quality of split.

      Q3) Comparing 2 decision trees based on their corresponding criterion (gini or entropy)

      Q4) Finding optimal tree depth (corresponding to maximum accuracy).

      Q5) Found feature importance from the trained model and rebuilt the model using the top 10 features only to check for information loss.


II. 2020A2PS1777P_KNN
   
      Dataset used: spambase_data.csv

      Q1) Normalized the dataset (using min-max normalization) and applied 3-NN using both Euclidean and Manhattan distance

      Q2) Trained both the 3-NN classifiers and compared their accuracy

      Q3) Finding the accuracy of a rote learner (k=1)

      Q4) Finding the accuracy of models for K ranging from 1 to 20 using euclidean distance and k-fold cross-validation.

      Q5) Plot the graph between K and corresponding accuracy to find optimal value of K.

      Q6) Performed Q4 and Q5 with Manhattan distance measure.

      Q7) Implemented weighted K-NN model. Used k-fold cross-validation for train-test split.

      Q8) Found the optimal K value for weighted KNN


III. 2020A2PS1777P_Naive_Bayes
     
     Dataset used: bank_data.csv, car_data.csv
     
     Performed Label Encoding of categorical features
     
     Q1) Created a Naive-Bayes Classifier. Dropped attribute 'current_act'. Found the accuracy of newly created Naive-Bayes Classifier and compared with the original one.
     
     Q2) Applied KNN classifier with and without attribute 'current_act'. Compared observations of KNN and Naive-Bayes Classifier.
     
     Q3) Applied Naive-Bayes classifier on car.csv dataset
     
     Q4) Found the correlation between attributes of car.csv dataset and the target variable, and arranged them in ascending order.
     
     Q5) Removed one of the highly correlated attributes and applied Naive-Bayes classifier. Compared the perofrmance of obtained model with that of earlier models.
     
IV. 2020A2PS1777P_Ensemble

    Dataset used: letter-recognition.csv
    
    Q1) Ensemble Method by Manipulation of Dataset
        Implemented Bagging classifier using 5 decision trees as base classifiers.
        Trained the model using k-fold cross-validation with k=5.
    
    Q2) Ensemble Method by Manipulation of Classifiers
        Base classifiers used: Decision Tree, 3-NN with Euclidean distance, 5-NN with Manhattan distance and Naive-Bayes classifier.
        Created an ensemble of classifiers using VotingClassifier with hard-voting method.
        
    Q3) Ensemble Method by Manipulation of Features
        Generated 5 feature sets using random vector.
        Applied Decision Tree with same hyperparameters on these 5 feature sets.
        Created an ensemble of classifiers using VotingClassifier with hard-voting method.
        
V. 2020A2PS1777P_clusterval
    
    In Progress
