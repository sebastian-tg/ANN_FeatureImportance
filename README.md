# ANN_FeatureImportance
Permutation feature importance for ANN models

This jupyter notebook provides routines to evaluate feature importances of an existing ANN model using the permutation method. In this method,  
each feature vector in the test set is randomly shuffled in turn, and the corresponding mean decrease in the accuracy of the predictions over
N iterations gives the importance of the feature. A sample ANN model that predicts the origin of GCs based on observables is provided and used 
as an example of the code implementation. The notebook includes the implementation of a method to eliminate biased importances due to highly
covariant features.
