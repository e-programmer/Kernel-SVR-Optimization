# Kernel-SVR-Optimization
Optimization of support vector regression on a dataset of superconductivity provided by the UCI repository
The project utilizes the nump, pandas and scikit learn libraries.
The goal was to find the best optimization of the kernel Support Vector Regressor to fit the data.
Maximum likelihood principal component analysis was used to determine the most appropriate features for the model.
Grid search algorithm was used to test various configurations of the svm to determine which one had the best adjusted r square score.
5-fold cross validation was used to validate the scoring.
