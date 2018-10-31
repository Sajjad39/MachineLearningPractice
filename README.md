# Machine Learning Practice

Some practices using statistical machine learning technique based on some dataset.

## Environment

* Using Python 3

### Dependencies

* `numpy`: For low-level math operations
* `pandas`: For data manipulation
* `sklearn` - [Scikit Learn](http://scikit-learn.org/): For evaluation metrics

* [`cvxopt`](http://cvxopt.org/): For convex optimization problem (for SVM)

## Projects

Subject|Technique|Dataset|Solution|Notes
-------|---------|-------|--------|-----
Letter Recognition|[kNN](Algorithm/kNN/kNN.md)|[Letter Recognition Datasets](https://archive.ics.uci.edu/ml/datasets/letter+recognition) ([File](Datasets/letter-recognition.csv))|[kNN From Scratch](Algorithm/kNN/kNN_Letter_Recognition/kNN_Letter_Recognition_FromScratch.py), [kNN Scikit Learn](Algorithm/kNN/kNN_Letter_Recognition/kNN_Letter_Recognition_sklearn.py)|[Notes](Notes/Subject/Letter_Recognition.md)
Page Blocks Classification|[Decision Tree](Algorithm/DecisionTree/DecisionTree.md)|[Page Blocks Classification Data Set](https://archive.ics.uci.edu/ml/datasets/Page+Blocks+Classification) ([File](Datasets/page-blocks.csv))|[Decision Tree (CART) From Scratch](Algorithm/DecisionTree/DecisionTree_Page_Blocks_Classification/DecisionTree_Page_Blocks_Classification_FromScratch.py), [Decision Tree Scikit Learn](Algorithm/DecisionTree/DecisionTree_Page_Blocks_Classification/DecisionTree_Page_Blocks_Classification_sklearn.py)|[Notes](Notes/Subject/Page_Blocks_Classification.md)
CSM|[Linear Regression](Algorithm/LinearRegression/LinearRegression.md)|[CSM Dataset (2014 and 2015)](https://archive.ics.uci.edu/ml/datasets/CSM+%28Conventional+and+Social+Media+Movies%29+Dataset+2014+and+2015) ([File](Datasets/2014-and-2015-CSM-dataset.csv))|[Linear Regression From Scratch](Algorithm/LinearRegression/LinearRegression_CSM/LinearRegression_CSM_FromScratch.py), [Linear Regression Scikit Learn](Algorithm/LinearRegression/LinearRegression_CSM/LinearRegression_CSM_sklearn.py)|[Notes](Notes/Subject/CSM.md)
Nursery|[Naive Bayes](Algorithm/NaiveBayes/NaiveBayes.md)|[Nursery Data Set](https://archive.ics.uci.edu/ml/datasets/nursery) ([File](Datasets/nursery.csv))|[Gaussian Naive Bayes From Scratch](Algorithm/NaiveBayes/NaiveBayes_Nursery/NaiveBayes_Nursery_FromScratch.py), [Gaussian Naive Bayes Scikit Learn](Algorithm/NaiveBayes/NaiveBayes_Nursery/NaiveBayes_Nursery_sklearn.py)|[Notes](Notes/Subject/Nursery.md)
Post-Operative Patient|[SVM](Algorithm/SVM/SVM.md)|[Post-Operative Patient Data Set](http://archive.ics.uci.edu/ml/datasets/post-operative+patient) ([File](Datasets/post-operative.csv), [Simplified](Datasets/post-operative-binary.csv))|[SVM From Scratch (using cvxopt and simplified dataset)](Algorithm/SVM/SVM_Post_Operative_Patient/SVM_Post_Operative_Patient_Simplified_FromScratch.py), [SVM Scikit Learn](Algorithm/SVM/SVM_Post_Operative_Patient/SVM_Post_Operative_Patient_sklearn.py)|[Notes](Notes/Subject/Postoperative_Patient.md)
Student Performance|[AdaBoost](Algorithm/Adaboost/Adaboost.md)|[Student Performance Data Set](https://archive.ics.uci.edu/ml/datasets/Student+Performance) ([File](Datasets/student-mat.csv))|[AdaBoost From Scratch](Algorithm/Adaboost/Adaboost_Student_Performance/Adaboost_Student_Performance_FromScratch.py), [AdaBoost Scikit Learn](Algorithm/Adaboost/Adaboost_Student_Performance/Adaboost_Student_Performance_sklearn.py)|[Notes](Notes/Subject/Student_Performance.md)
Sales Transactions|[k-Means](Algorithm/KMeans/KMeans.md)|[Sales_Transactions_Dataset_Weekly](http://archive.ics.uci.edu/ml/datasets/sales_transactions_dataset_weekly) ([File](Datasets/Sales_Transactions_Dataset_Weekly.csv))|[k-Means From Scratch](Algorithm/KMeans/KMeans_Sales_Transactions/KMeans_Sales_Transactions_FromScratch.py), [k-Means Scikit Learn](Algorithm/KMeans/KMeans_Sales_Transactions/KMeans_Sales_Transactions_sklearn.py)|[Notes](Notes/Subject/Sales_Transactions.md)
Frequent Itemset Mining|[FP-Growth](Algorithm/FP-Growth/FP-Growth.md)|[Retail Market Basket Data Set](http://fimi.ua.ac.be/data/) ([File](Datasets/retail.csv))|[FP-Growth From Scratch](Algorithm/FP-Growth/FP-Growth_Frequent_Itemset_Mining/FP-Growth_Frequent_Itemset_Mining_FromScratch.py)|[Notes](Notes/Subject/Frequent_Itemset_Mining.md)
Automobile|[PCA](Algorithm/PCA/PCA.md)|[Automobile Data Set](http://archive.ics.uci.edu/ml/datasets/Automobile) ([File](Datasets/imports-85.csv))||[Notes](Notes/Subject/Automobile.md)
Handwriting Digit|[SVM](Algorithm/SVM/SVM.md)|[MNIST](http://yann.lecun.com/exdb/mnist/) ([File](Datasets/MNIST.csv))|[SVM From Scratch](Algorithm/SVM/SVM_MNIST/SVM_MNIST_FromScratch.py)|[Notes](Notes/Subject/MNIST.md)
Labor Relations|-|[Labor Relations Data Set](https://archive.ics.uci.edu/ml/datasets/Labor+Relations)||[Notes](Notes/Subject/Labor_Relations.md)

## Machine Learning Categories

### Consider the learning task

* **Surpervised Learning**
    * *Classification* - Discrete
    * *Regression* - Continuous
* **Unsupervised Learning**
    * *Clustering* - Discrete
    * *Dimensionality Reduction* - Continuous
    * *Association Rule Learning*

* **Semi-supervised Learning**
* **Reinforcement Learning**

### Cosider the desired output of a ML system

* *Classification*
    * `Logistic Regression`
    * `k-Nearest Neighbors (kNN)`
    * `Support Vector Machine (SVM)` - [Deduction](Algorithm/SVM/SVMDeduction.md)
    * `Naive Bayes`
    * `Decision Tree (ID3, C4.5, CART)`
* *Regression*
    * `Linear Regression`
    * `Tree (CART)`
* *Clustering*
    * `k-Means`
    * `Hierarchical Clustering`
* *Association Rule Learning*
    * `Apriori`
    * `Eclat`
    * `FP-growth` - Frequent itemsets mining
* *Dimensionality Reduction*
    * `Principal Compnent Analysis (PCA)`
    * `Single Value Decomposition (SVD)`
    * `Linear Discriminant Analysis (LDA)`

### Ensemble Method (Meta-algorithm)

* Bagging
    * `Random Forests`
* Boosting
    * `AdaBoost`

## [Machine Learning Concepts](Notes/MachineLearningConcepts.md)

* [Data Preprocessing](Notes/MachineLearningConcepts.md#Data-Preprocessing)
    * [Training and Test Sets - Splitting Data](Notes/MachineLearningConcepts.md#Splitting-Data)
    * [Missing Value](Notes/MachineLearningConcepts.md#Missing-Value)
* [Model Evaluation](Notes/MachineLearningConcepts.md#Model-Evaluation)
    * [Classification](Notes/MachineLearningConcepts.md#Classification)
    * [Regression](Notes/MachineLearningConcepts.md#Regression)
    * [Clustering](Notes/MachineLearningConcepts.md#Clustering)
* [Fitting and Model Complexity](Notes/MachineLearningConcepts.md#Fitting-and-Model-Complexity)
    * [Overfitting](Notes/MachineLearningConcepts.md#Overfitting)
    * [Underfitting](Notes/MachineLearningConcepts.md#Underfitting)
    * [Generalization](Notes/MachineLearningConcepts.md#Generalization)
    * [Regularization](Notes/MachineLearningConcepts.md#Regularization)
* [Reducing Loss](Notes/MachineLearningConcepts.md#Reducing-Loss)
    * [Learning Rate](Notes/MachineLearningConcepts.md#Learning-Rate)
    * [Gradient Descent](Notes/MachineLearningConcepts.md#Gradient-Descent)
* [Other Learning Method](Notes/MachineLearningConcepts.md#Other-Learning-Method)
    * [Lazy Learning](Notes/MachineLearningConcepts.md#Lazy-Learning)
    * [Incremental Learning (Online Learning)](Notes/MachineLearningConcepts.md#Incremental-Learning-(Online-Learning))

## Machine Learning Mathematics

### Topic

* [Convex Optimization](Notes/Math/Topic/ConvexOptimization.md)

### Core

* Linear Algebra
    * Hessian Matrix
    * Quadratic Form
* Calculus
    * [Multivariable Deratives](Notes/Math/Calculus/MultivariableDeratives.md)
        * Quadratic Approximations
        * Lagrange Multipliers and Constrained Optimization
        * Lagrange Duality
* Probability and Statistics

### Basics

* Algebra
* Trigonometry

## Books Recommand

* [**Machine Learning in Action**](https://www.manning.com/books/machine-learning-in-action)
    * [Source Code](https://manning-content.s3.amazonaws.com/download/3/29c6e49-7df6-4909-ad1d-18640b3c8aa9/MLiA_SourceCode.zip)

## Resources

### Tutorial

#### Videos

* [Google - Machine Learning Recipes with Josh Gordon](https://www.youtube.com/playlist?list=PLOU2XLYxmsIIuiBfYad6rFYQU_jL2ryal)
    * [Josh Gordon's Repository](https://github.com/random-forests)
* [Youtube - Machine Learning Fun and Easy](https://www.youtube.com/playlist?list=PL_Nji0JOuXg2udXfS6nhK3CkIYLDtHNLp)

* [Siraj Raval - The Math of Intelligence](https://www.youtube.com/playlist?list=PL2-dafEMk2A7mu0bSksCGMJEmeddU_H4D)
    * [Siraj Raval's Repository](https://github.com/llSourcell)

#### Documentations

* [ApacheCN](http://ailearning.apachecn.org/) (ML, DL, NLP)
    * [Github - AiLearning](https://github.com/apachecn/AiLearning)
    * [Official Website - ApacheCN 中文開源組織](http://www.apachecn.org/)

#### Interactive Learning

* [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course/)
* [Kaggle Learn Machine Learning](https://www.kaggle.com/learn/machine-learning)

#### MOOC

* [Stanford Andrew Ng - CS229](http://cs229.stanford.edu/)
    * [Coursera](https://www.coursera.org/learn/machine-learning)

### Github

* [Machine Learning from Scratch (eriklindernoren/ML-From-Scratch)](https://github.com/eriklindernoren/ML-From-Scratch)
* [Jack-Cherish/Machine-Learning](https://github.com/Jack-Cherish/Machine-Learning)

### Datasets

* [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.html)
* [The MNIST Database of handwritten digits](http://yann.lecun.com/exdb/mnist/)

### Machine Learning Platform

* [Kaggle](https://www.kaggle.com/)
* [OpenML](https://www.openml.org/)
