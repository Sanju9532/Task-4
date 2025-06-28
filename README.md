Introduction: 
          Importing the dataset, handle missing values, split the data into training and testing sets, standardize the input features, and fiting a Logistic Regression model. 
Evaluating the model using a confusion matrix, precision, recall, and ROC-AUC, and finally, tuning the classification threshold.

Handling Missing Values: 
        There are a total of 33 columns in the dataset. The unnamed column contains no data and consists entirely of null values, so removing that column. 
Additionally, converting the target column to a numerical format using label encoding.

Building Model: 
        Standardize the input features using StandardScaler, and then fit the Logistic Regression model. The model will predict probabilities with a default threshold of 0.5. 
Finally, evaluate the model using a confusion matrix, with precision scores of 0.99 for both training and testing, recall scores of 0.98 for training and 0.94 for testing, 
and ROC-AUC scores of 0.99 for training and 0.97 for testing.
