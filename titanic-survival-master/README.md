# Titanic-Survival
This is analaysis of survival of People from Titanic dataset on kaggle.For more description of data please refer this https://www.kaggle.com/c/titanic/data



## Pre-Processing of data  
  
  Detecting outliners and removing them since they can have significant effect in regression.
  
  Filling or removing missed values depending on availaility of data.
  
  Reducing Skewness of data using Log Tansformation.
  
  Creating categorical values for Character data type.

## Visualising data
  
  Describing,summarizing of data.
  
  Correlation matrix for finding relationship between varibales. 
  
  Plotting Survival Probability for eight different factors given.
  
  Visualising data with Box plots.

## Modelling 
  
  Used 10 popular classifiers and evaluated the mean accuracy of each of them by a stratified kfold cross validation procedure.
  
  SVC

  Decision Tree

  AdaBoost

  Random Forest

  Extra Trees

  Gradient Boosting

  Multiple layer perceprton (neural network)

  KNN

  Logistic regression

  Linear Discriminant Analysis

  ## Hyper tuning for best models
    
    Performed a grid search optimization for AdaBoost, ExtraTrees , RandomForest, GradientBoosting and SVC classifiers.
  
  ## Ensemble modelling
     
     Choosed a voting classifier to combine the predictions coming from the 5 classifiers.
          
For complete analayis and visualisations of data please read the ipython notebook.
