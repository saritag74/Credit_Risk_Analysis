#                                                             Credit_Risk_Analysis

BalancedRandomForestClassifier
    BalanacedRandomForestClassifier is a varient of RandomForest algorithm.
In this modoule we had to acomidate Jill with doing this report to see the risk between the good loan and the risk loans 
This will requiered to use different techniques to train and evalite models with unbalances classes.
Since Jill ask ti use the imbalances-learn and sckit=learn libaries to evalute and build samples bby using resampling.
the algarithom that we will be using will be the following RandomOverSampler and SMOTE and undersample the data using the ClusterCentroids algorithm.

An accuracy score for the model is calculated (2.5 pt)
# Calculated the balanced accuracy score
from sklearn.metrics import balanced_accuracy_score
predictions = log_model.predict(X_test)
balanced_accuracy_score(y_test, predictions)

0.6297447180326836

this is a copy of one of the accuracy score for the first delivrable(CreditRisk resampling)
this is the balanced Accurary of the the randomsampler
in here the percentage was 62%

SMOTE:
# Calculated the balanced accuracy score
predictions = s_model.predict(X_test)

balanced_accuracy_score(y_test, predictions)
0.6259541727204436

the outcome of SMOTE  is 62%

# Calculated the balanced accuracy score
from sklearn.model_selection import train_test_split
predictions = c_model.predict(X_test)
balanced_accuracy_score(y_test,predictions)

0.5441753293779491

This is the out come of the ClusterCentroids which is 54%

<img width="663" alt="Screen Shot 2023-02-27 at 7 54 15 PM" src="https://user-images.githubusercontent.com/115046550/221724093-c3bbd1ea-a973-4176-978b-239b69439cdd.png">

SMOTTEN

  # Calculated the balanced accuracy score
predictions = s_model.predict(X_test)
balanced_accuracy_score(y_test,predictions)

0.6153581886799242

the outcome of the SMOTTEEN is 61%

BalancedRandomForestClassifier FROM the module creidt risk ensemble

# Calculated the balanced accuracy score
predictions = balranforcla_model.predict(X_test)

balanced_accuracy_score(y_test, predictions)
0.7877672625306695

the outcome of this is 78%

Easy Ensemble AdaBoost Classifie

  # Calculated the balanced accuracy score
predictions = esenclas_model.predict(X_test)

balanced_accuracy_score(y_test, predictions)
0.934075242434864
this one is 93%

SUMMARY

    if We use Ensemble  classifie we can see that is has one of the highest Percentage  of high risk. the percentage is (#%
   while in the other hand using randome it gave us a lower percantge. i would use Ensemble classifie more.




