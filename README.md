# KNN
Feature selection with Nearest neighbor

It is a well-known fact that the nearest neighbor algorithm is a very good choice for classification tasks. It is a very simple yet effective classification algorithm. However one of the major drawbacks of this algorithm is that it is very sensitive to irrelevant features. 

In this project, I have implemented feature selection along with the nearest neighbors algorithm. I have imaplemeted 2 kinds of feature selection-
1. Forward selection - Forward feature selection is an iterative approach in which we start with having no features and then we iteratively add features to the dataset based on testing these features with the nearest neighbor algorithm. These features are then tested in conjunction with the existing list of features that obtain the highest accuracy.
2. Backward elimination -  This is a feature selection method in which we start with all the features and then iteratively remove the features to try and obtain a higher accuracy until we are left with only a single feature.

This project was a part of the Artificial Intellignece course by Dr. Eamonn Keogh.
