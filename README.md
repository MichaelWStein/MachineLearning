# MachineLearning
Contains files related to machine learning.

There are two files related to classification with support of Machine Learning 
- ExoplanetVectorMachine for identification of exoplanets with the SVC, linear kernel (from sklearn)
- ExoplanetRandomTree for identification of exoplanets with random tree (also from sklearn).

Both programs were optimized with Gridsearch.

Accuracy: 
Vectormachine: 0.840 before hyperparameter tuning, 0.878 after hyperparameter tuning 
Random Tree: 0.887 before hyperparameter tuning, 0.895 after hyperparameter tuning

Note that the Random tree model tends to overfit (Training Data Score was 1.0 before hyperparameter tuning.
