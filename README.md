# magic_mushroom
Datathon to classify mushrooms as poisonous or edible

The purpose of this project is to apply under time pressure a series of modelling techniques to see how to explore, transform and model the Mushroom dataset.

For the purposes of this project I have run some exploratory analysis, correlations and visualisations to see how the underlying data relate to the target variable 'class'.

Once the data is prepared this is run through a series of classification models, with errors reported and visualised. There is some heavy borrowing from other approaches here, as I am using it as an attempt to improve my python + machine learning skills. 

Steps followed:
-Import various libraries 
-Read training data
-Check for missing values and remove or impute (fill forward)
-Use LabelEncoder function to change from categorical to integer data to facilitate further analysis
-Explore basic structure and statistics of the data
-Visualise data
-Create Correlation Matrix to see variable relationships and correlations
-Look a bit deeper at three variables but not too exhaustive here
-Basic preprocessing of data involving: 
  -Creating X and y variables
  -Creating the Training and Test data split
  -Applying the standard scaler to create consistent scales
  
- Apply the following models from SciKit Learn:
  -Decision Tree, 
  -Gaussian Naive Bayes, 
  -Random Forest, 
  -K Nearest Neighbour, 
  -Logistic Regression 

- For each model the approach is the same (where possible and methods are supported within SciKitLearn):
- Fit the model to the training data
- Apply the fit model to the test data and predict the 'class' label
  -Generate and visualise a confusion matrix
  -Create a canned Error Report per model focusing on Precision, Recall, F1 Score, Support
  -Create an ROC curve visualisation
  -Plot the ROC curve to show False Positives and True Positives

  
  
