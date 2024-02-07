# Credit Risk Analysis Report

### Overview:
#### In this code we are testing this machine learning model to analyis whether or not it is a good fit for our credit risk analysis. We are loading the data into two sets. A training set and a testing set. We are then loading this data into a logistic regression model and making predictions on the data. The data is then resampled and ran in a logistic regression model using resampled data to further test the machine learning model's capability. 

- #### Both original and resampled data sets have an accuracy score of .99

- #### The precision score for healthy loans (0) stays the same between both data sets. However, the high-risk loans (1), saw a .01 drop in precision in our resampled data versus our original data. 

- ### Recall scores for healthy loans (0) remained at .99 for both original and resampled data sets. The high-risk loans (1) saw an increase in score of .08 in resampled data over the original data sets recall score of .91

### Summary:
#### When looking at the outputs from our original test data and our resampled data we saw an overall increase in performance when resampling occured. The precision of the model dropped, but the recall score saw a major increase in effectiveness in capturing high-risk loans. The outcome of the precision score is subjective, but the overall performance of the machine learning model is impressive. This model could be highly favorable if the precision score is within an acceptable range for the business's model. 

### Here is our original data output:
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
    macro avg       0.92      0.95      0.94     19384
    weighted avg       0.99      0.99      0.99     19384

### Here is our resampled data output:
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

    accuracy                           0.99     19384
    macro avg       0.92      0.99      0.95     19384
    weighted avg       0.99      0.99      0.99     19384