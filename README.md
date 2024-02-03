# Titanic_survival_predection
# Author -  Sunny singh 
# Domain - Data Science 
# AIM - 
  The aim of this project is to build a model that predicts whether a passenger on the Titanic survived or not based on given features.
# Data set - 
  The dataset for this project is imported from a CSV file, "archive.zip". The dataset contains information about passengers on the Titanic, including their survival 
  status, class (Pclass), sex (Gender), and age (Age).

# Libraries Used - 
  The following libraries are used : - 
 
  -> numpy 
  -> pandas
  -> matplotlib.pylot 
  -> seaborn 
  -> train_test_split from sklearn.model_selection
  -> LogisticRegression from sklearn.linear_model 
  -> accuracy_score from sklearn.metrics

  # Model Training 
  1.  The feature matrix X and target vector Y were created using relevant columns from the DataFrame.
  2.  The dataset was split into training and testing sets using train_test_split from sklearn.model_selection.
  3.  A logistic regression model was initialized and trained on the training data using LogisticRegression from sklearn.linear_model.
