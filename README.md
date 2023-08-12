# ClusteringAnimals
 Leveraging unsupervised learning models and algorithms to cluster unlabeled animal data exemplifies advanced techniques for data-driven categorization.


## Problem Statement
Consider the dataset "zoo.csv" and look at the information provided in the first 5 rows.
The first column denotes the animals name and the last one specifies the high-level class for the corresponding animals.
You are supposed to find a solution to the following question:
1. Identify the unique unmber of high-level classes.
2. Perform agglomerative clustering using the 16 intermediate features
3. Compute the mean squared error by comparing the actual high-level class and predicted high-level class
In a nutshell, you just have to perform agglomerative clustering with the appropriate MSE value

## Steps Covered
1. Importing Libraries and dataset
2. Checking for missing values
3. Identifing unique labels and plot them
4. Extracting features necessary for clustering within a single variable
5. Fitting agglomerative clustering model onto the feature data
6. Predicting labels for each animal
7. Pringint the RMSE of the model
   

