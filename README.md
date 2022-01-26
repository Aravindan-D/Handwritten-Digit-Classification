# Handwritten-Digit-Classification

In this project the dataset we used was taken from the UCI machine learning repository in the name of Pen-Based Recognition of Handwritten Digits Data Set.
And I performed data standardisation ,PCA and other feature engineering and feature extaction techniques.

**1]**  The k-nearest neighbors method, how would you explain its use within the industry?


  The k-nearest neighbours is a supervised machine learning algorithm mostly used for classification and regression problems and some and some times KNN is also used for Recommendation systems. KNN will work by finding the nearest neighbour of the given input

   Changing the values of K that is the number of nearest neighbours will result in good accuracy. we can find it by creating a for loop and iterate over each values and we can find the best value of K to develop a model with good accuracy



  **KNN** algorithm follows three different Distance measurements of data points.


1. Euclidean Distance
2. Manhattan Distance
3. Minkowski  Distance

2] Identify one software tool used to implement and test a k-nearest neighbors model. For this tool, provide a brief explanation of its use and purpose within a real-world scenario?


The software tool used for implementing the k-nearest neighbours algorithm is Scikit-Learn, a library from python. This library has inbuilt algorithms that can be accessed from the library with a function call of KNeighborsClassifier() with parameters such as the distance of the nearest neighbour and method used to find the distance.

The developed model can be tested with the help of a predict function in sklearn Its metrics can be predicted with the help of ROC curve which can be accessed with the help of sklearn library with the help of roc_auc_score() function in it.

It is used to build the real world models faster and efficient with its pre built functions .some of the real-world applications are recommendation system, weather prediction etc..

