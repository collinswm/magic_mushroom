# Classify which mushrooms are poisonous and which are edible?

# Objective
Datathon to classify mushrooms as poisonous or edible. The ideal situation is that we are aiming to create a model which can predict with 100% certainty that all mushrooms which are poisonous are actually classified as poisonou. The cost of incorrectly predicting is very high - you can recommend a mushroom as edible when it can be highly toxic. 

# Process
The process followed has been to develop the material here under time pressure using a series of modelling techniques to explore, transform and model the Mushroom dataset.

#Steps Followed

1. Prepare and process data: 

-Import various libraries 
-Read training data
-Check for missing values and remove or impute (fill forward)
-Use LabelEncoder function to change from categorical to integer data to facilitate further analysis
-Explore basic structure and statistics of the data
-Visualise data
-Create Correlation Matrix to see variable relationships and correlations
-Look a bit deeper at three variables but not too exhaustive here
-Basic preprocessing of data involving: 
  -Create X and y variables
  -Create the Training and Test data split (80%: 20%)
  -Apply the standard scaler to create consistent scales
  
2. Identify a series of models to the training data:

For all models below, fit the model to the training data and apply the fitted data to the test data to predict the 'class' label within the test set (20%)
-Decision Tree, 
-Gaussian Naive Bayes, 
-Random Forest, 
-K Nearest Neighbour, 
-Logistic Regression 

3.  the output of the models: 
-Report on Classification metrics and visualise: 
-Generate and visualise a confusion matrix
-Create a canned Error Report per model focusing on Precision, Recall, F1 Score, Support
-Create an ROC curve visualisation
-Plot the ROC curve to show False Positives and True Positives
