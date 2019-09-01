# Statistical-Learning
- Semester: NTU-10702 Statistical-Learning: Theory and Practice
- Course Info: [syllabus](https://github.com/tzuhsuancheng/Statistical-Learning/blob/master/syllabus%202019%20v1.pdf)

## Final Project: Pet Finder

## Kaggle Competition

## HW1: KNN model
We are going to use a subset of the "Million Songs Dataset" in this question. The dataset has been pre-processed and the training and testing dataset has been splitted and stored in a dictionary data structure. You can load the data from msd_data1.pickle using pickle.load(). There are four elements in the dictionary: X_train, Y_train, X_test, Y_test. As indicated by their names, these four elements are training and testing data. The outcome variable (i.e.  y ) is the year a song was released, and the features are variables that characterize the sound of a song. The goal is to predict the release year given sound features.
- [HW1](https://github.com/tzuhsuancheng/Statistical-Learning/blob/master/HW1/homework1.ipynb)

## HW2: All about regressions
Linear regression is one of the essential parametric models in statistical learning. We have discussed three types of regression models: ordinary least squares (OLS), ridge regression, and lasso regression. OLS can be learned as long as the training features are linearly independent. Ridge regression adopts L2 regularization for model learning, and Lasso adopts L1 regularization. Surprisingly, the prediction accuracy of the three types of models may be heavily influenced by how we preprocess the features and outcome values. We are going to explore these aspects in this homework.
- [HW2](https://github.com/tzuhsuancheng/Statistical-Learning/blob/master/HW2/HW2.ipynb)
