# classification-of-iris-flowers-ML
First of all why in Python?
Python is a popular and powerful interpreted language. Unlike R, Python is a complete language and platform that you can use for both research and development and developing production systems.There are also a lot of modules and libraries to choose from, providing multiple ways to do each task. It can feel overwhelming.


A machine learning project may not be linear, but it has a number of well known steps:
Define Problem.
Prepare Data.
Evaluate Algorithms.
Improve Results.
Present Results.


There are 5 key libraries that you will need to install.
-scipy
-numpy
-matplotlib
-pandas
-sklearn

The dataset contains 150 observations of iris flowers. There are four columns of measurements of the flowers in centimeters. The fifth column is the species of the flower observed. All observed flowers belong to one of three species.

Data Visualization
1 - Univariate plots to better understand each attribute.(box and whisker plots, histogram etc)
2 - Multivariate plots to better understand the relationships between attributes.(scatter plots etc)

We will split the loaded dataset into two, 80% of which we will use to train our models and 20% that we will hold back as a validation dataset.

We will use 10-fold cross validation to estimate accuracy.
This will split our dataset into 10 parts, train on 9 and test on 1 and repeat for all combinations of train-test splits.

Let’s evaluate 6 different algorithms:
- Logistic Regression (LR)
- Linear Discriminant Analysis (LDA)
- K-Nearest Neighbors (KNN).
- Classification and Regression Trees (CART).
- Gaussian Naive Bayes (NB).
- Support Vector Machines (SVM).
This is a good mixture of simple linear (LR and LDA), nonlinear (KNN, CART, NB and SVM) algorithms. We reset the random number seed before each run to ensure that the evaluation of each algorithm is performed using exactly the same data splits. It ensures the results are directly comparable.

We can see that it looks like KNN has the largest estimated accuracy score.
