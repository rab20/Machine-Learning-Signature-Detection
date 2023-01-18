# Machine-Learning-Signature-Detection

## Problem Statement
Dataset: Signature detection
https://drive.google.com/file/d/1-vYDuTG8htJC7aO- OwoNbhs4Zdw4xbBD/view?usp=sharing
Import Libraries/Dataset
<br> 1. Download the dataset
<br> 2. Import the required libraries
### 1. Data Visualization and Exploration 
  <br> 1. Print 2 rows for sanity check to identify all the features present in the dataset and if the target matches with them.
  <br> 2. Comment on class imbalance with appropriate visualization method.
  <br> 3. Provideappropriatevisualizationstogetaninsightaboutthedataset.
  <br> 4. Do the correlational analysis on the dataset. Provide a visualization for the
  same. Will this correlational analysis have an effect on feature selection that you will perform in the next step? Justify your answer. Answers without justification will not be awarded marks.
  <br> 5. Any other visualization specific to the problem statement.
### 2. Data Pre-processing and cleaning 
  <br> 1. Do the appropriate pre-processing of the data like identifying NULL or Missing Values if any, handling of outliers if present in the dataset, skewed data etc. Mention the pre-processing steps performed in the markdown cell. Explore a few latest data balancing tasks and its effect on model evaluation parameters.
  <br> 2. Apply appropriate feature engineering techniques for them. Apply the feature transformation techniques like Standardization, Normalization, etc. You are free to apply the appropriate transformations depending upon the structure and the
  complexity of your dataset. Provide proper justification. Techniques used without justification will not be awarded marks. Explore a few techniques for identifying feature importance for your feature engineering task.
### 3. Model Building 
  <br> 1. Split the dataset into training and test sets. Answers without justification will not be awarded marks. 
  <br> Case 1 : Train = 80 % Test = 20% [ x_train1,y_train1] = 80% ; [ x_test1,y_test1] = 20% ;
  <br> Case 2 : Train = 10 % Test = 90% [ x_train2,y_train2] = 10% ;
  [ x_test2,y_test2] = 90%
  <br> 2. Explore k-fold cross validation. 
  <br> 3. Build Model/s using 1) Logistic Regression 2) MLE 3) Any other appropriate
  model 
  <br> 4. Explore the need of regularization and incorporate few relevant techniques for
  the problem statement. 
  <br> 5. Compare models with and without regularization in a tabular format and justify the findings.
### 4. Performance Evaluation 
  <br> 1. Do the prediction for the test data and display the results for the inference. Calculate all the evaluation metrics and choose best for your model. Justify your answer. Answers without justification will not be awarded marks. 
  <br> 2. Comment on underfitting/overfitting/just right model. Justify your comment. Answers without justification will not be awarded marks. 
