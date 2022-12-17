# FinalProject
I try to use random forest and it's not good at the actual data. 
Because this data set is brain tumor classification, we need to pocess the photos, so svm is the best model.
For the hyper parameter, the method I choose the hyper parameter is use the "sklearn.model_selection" package. And we used GridSearchchCV function and know that the best model is "kernel='rbf', degree=1, C=100"
