# Databricks Machine Learning Projects 

  

## PROBLEM STATEMENT  

The dataset(FaultDataset.csv) used in this project is sample data from vibration sensors in a manufacturing company setting. The imaginary company uses  
vibration sensors to monitor the machinery within their production line and want to use this data for predictive maintenance – the aim is to be able  
to classify whether there is a fault with the machine based on the readings from the vibration sensors.  Each row contains twenty vibration sensor readings, and the final
column identifies whether there was a fault with the machine at the time of the readings. In this column, 0 means there was no fault with the machine and 1 means a fault was identified. 

## TASK  

1. The uploaded datasets, must exist (and be named) in the following locations:/FileStore/tables/FaultDataset.csv 

2) Load the data into Spark DataFrame 

3) Exploratory analysis or carrying out of visualization prior to training 

4) Carry out Data preparation and pre-processing prior to training the model 

5) Selection of hyperparameters and model training and evaluation and MLflow experiment tracking 


### Extra: 

I used multiple runs as part of my experiment, for example, training models with different hyperparameters. I also used 3 different models which include DecisionTree Classifier, RandomForest classifier and Gradient-Boosted trees classifier.  
From the results, both the random forest and gradient boosted tree classifiers outperform the decision tree classifier, with identical accuracy  
of 97.01% for the former two. However, the performance of these models cannot be evaluated based solely on their accuracy, and it's important to consider other metrics  
such as precision, recall, and F1-score, as well as their respective training times, model complexity, and interpretability, among other factors. 


