# Dry-Bean-Data-Analysis

Dataset: https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset

First we loaded data and got know something more about it. Next - data has been splitted into train and test sets. We also remove high correlated (redundant) features with setting max correlation threshold. Next - our approach was to first train model with training data and next - test it for test data. NC turned out the worst model - accuracy was only 73% - the same for training and test data. In case of NN and kNN we can see some differences. NN training accuracy is 100%, but only 83% for test data. We can see there an overfitting problem, but it was really easy to deal with it - we increase number of nearest neighbours. First, we tested k numbers in range (1-50) and choose one with the best accuracy score. Then - our training accuracy was 90%, but the most important one - for test data - increased up to 88% for 21 neighbours. Each class has been predicted really fine with our models. 
