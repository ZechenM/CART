# CART
 Implementation of Classification and Regression Tree (CART) algorithm with training a decision tree for classification.

* Dataset
  * The Red Wine Quality Data Set with 1599 samples. 
  * Each sample has 11 features (attributes) and a quality score (QS) ranging from 0 to 10
  * https://archive.ics.uci.edu/ml/datasets/wine+quality
  * the samples are labelled into 3 different classes: ”good/2” (QS>6), ”normal/1” (QS=6), and ”bad/0” (QS<6) based on their quality scores
  * the data set is partitioned into a training set and a testing set including 1000 samples and 599 samples respectively
* Requirements
  * Each tree node should have either zero or two children nodes (binary split). Each node should be split based on one and only one feature.
  * Use gini impurity as the measure when making split decisions.
  * Implement 5-fold cross validation and grid search to find the best max_depth which is the only one parameter to be searched for.
