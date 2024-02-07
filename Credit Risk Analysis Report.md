# Credit Risk Analysis Report
#### In this code we are testing this machine learning model to analyis whether or not it is a good fit for our credit risk analysis. We are loading the data into two sets. A training and a testing set. We are then loading this data into a linear regression model and making predictions on the data. The data is then resampled and ran in a linear regression model using randomized resampled data to further test the machine learning model. 

- ### accuracy

- ### precision

- ### recall scores

#### Summary: When looking at the outputs from our original test data and our resampled data there are no major differences. 

### Here is our original data output
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
    macro avg       0.92      0.95      0.94     19384
    weighted avg       0.99      0.99      0.99     19384

### Here is our resampled data output

              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

    accuracy                           0.99     19384
    macro avg       0.92      0.99      0.95     19384
    weighted avg       0.99      0.99      0.99     19384

### 