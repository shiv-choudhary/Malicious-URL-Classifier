# Malicious-URL-Classifier

### As name suggest Malicious URL classifier is a machine learning model which will identify the given URL is malcious or not, used only lexical feature for model creation.Tokenization can be used.

Dataset has been taken from Kaggle, which consist of 450176 DataPoint

Steps followed in building the machine learning classifier:
  Data Preprocessing / Feature Engineering
  Data Visualization
  Building Machine Learning Models using Lexical Features only.
  
The label associated with each record contains the word "benign" if the URL is a good and "malicious" if it is malicious. DataSet is imbalanced till some extent, We can apply oversampling Technique(SMOTE). DataSet consist no NULL value.

Using three models for classification and comparison. 
  1. Logistic Regression 
  2. Decision Trees 
  3. Random Forest

Further Improvement Needed
  Analyse the code and tags used in the webpages.
  Reduce the class imbalance problem.
