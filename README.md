# Statistical-Learning
- Semester: NTU-10702 Statistical-Learning: Theory and Practice
- Course Info: [syllabus](https://github.com/tzuhsuancheng/Statistical-Learning/blob/master/syllabus%202019%20v1.pdf)

## Final Project: Pet Finder
We use the data from PetFinder.my, a Malaysia’s leading animal welfare, to predict the adoptability of pets. Our goal is to build a predictive model to help shelters and rescuers around the world on improving their pet profiles' appeal, reducing animal suffering and euthanization. According to the result, Random Forest method has the best performance.
- [Presentation](https://github.com/tzuhsuancheng/Statistical-Learning/blob/master/Final-project/project_petfinder.pdf)
- [Exploratory data analysis](https://drive.google.com/drive/folders/15fOS1TACWvyGVULFeincHjdgY81oh7e-?fbclid=IwAR1jHRoq3x89sPcI_VVg92fHspn03Jtpy9_ydMqT535i9IU3Q2GlWqMCvlk)
- [Models](https://drive.google.com/drive/folders/1Fb_RlaEd44mLGa0yHcEJQfWPlfQsOKw-?fbclid=IwAR1jHRoq3x89sPcI_VVg92fHspn03Jtpy9_ydMqT535i9IU3Q2GlWqMCvlk)

## Kaggle Competition
In this competition, we are going to build the model to predict the indusy(行業) and job occupation(職業).
- Leaderboard:
  - public socre: (9/20)
  - private score: (8/20)
- [More information](https://www.kaggle.com/c/2019sl)
- [code](https://github.com/tzuhsuancheng/Statistical-Learning/blob/master/Kaggle-competition/Final.ipynb)


## HW1: KNN model
We are going to use a subset of the "Million Songs Dataset" in this question. The dataset has been pre-processed and the training and testing dataset has been splitted and stored in a dictionary data structure. You can load the data from msd_data1.pickle using pickle.load(). There are four elements in the dictionary: X_train, Y_train, X_test, Y_test. As indicated by their names, these four elements are training and testing data. The outcome variable (i.e.  y ) is the year a song was released, and the features are variables that characterize the sound of a song. The goal is to predict the release year given sound features.
- [HW1](https://github.com/tzuhsuancheng/Statistical-Learning/blob/master/HW1/homework1.ipynb)

## HW2: All about regressions
Linear regression is one of the essential parametric models in statistical learning. We have discussed three types of regression models: ordinary least squares (OLS), ridge regression, and lasso regression. OLS can be learned as long as the training features are linearly independent. Ridge regression adopts L2 regularization for model learning, and Lasso adopts L1 regularization. Surprisingly, the prediction accuracy of the three types of models may be heavily influenced by how we preprocess the features and outcome values. We are going to explore these aspects in this homework.
- [HW2](https://github.com/tzuhsuancheng/Statistical-Learning/blob/master/HW2/HW2.ipynb)

## HW3: Classification models
### Generative Models 
We are going to explore the problem of identifying smartphone position through probabilistic generative models. Motion sensors in smartphones provide valuable information for researchers to understand its owners. An interesting (and more challenging) task is to identify human activities through the data recorded by motion sensors. For example, we want to know whether the smartphone owner is walking, running, or biking. In this homework problem, we are going to tackle a simpler problem. We want to know the static position of the smartphone.
- [HW3-1](https://github.com/tzuhsuancheng/Statistical-Learning/blob/master/HW3/assignment3-1.ipynb) 

### Logistic Regression with L2 Regularization
We are going to use to "Adult" dataset on the UCI machine learning reposition. The goal is to predict the label values of the income column, which can be either '>50K' or '<=50K.' The dataset had splitted the training and test data, and we are going to respect this particular train-test split in model testing.
- [HW3-2](https://github.com/tzuhsuancheng/Statistical-Learning/blob/master/HW3/assignment3-2.ipynb)

## HW4: Data Visualization via Dimensionality Reduction
We are going to visualize this competition relationships using the University Department Offer of Admission Dataset (UDOAD).
A large portion of high school students get admitted to universities through an application and screening process that require each university department of offer admission to applicants first before students can choose where they wants to go. If we think of applicants as the customers of an academic department, then the duplications of offered applicants for different departments can be used to understand the competition relationships between academic departments. 
- [HW4](https://github.com/tzuhsuancheng/Statistical-Learning/blob/master/HW4/assignment_4.ipynb)

## HW5: Time Series Predction
Time series prediction problem has a wide range of applications. We are going to explore this issue in this homework. To keep things simple, we are going to focus on the univariate time series, a time series with a single value in a period. The dataset contains 104 weeks of training data and 39 weeks of test data. The time series is the product sales of a supermarket in a particular period. The goal is to predict sales in the test period. 
- [HW5](https://github.com/tzuhsuancheng/Statistical-Learning/blob/master/HW5/hw5_qv1.ipynb)
