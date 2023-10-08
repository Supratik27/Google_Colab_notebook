**Machine Learning Classification Comparison on the IRIS Dataset**

**Introduction:**
This project is a comparative study of four different machine learning classification algorithms on the famous IRIS dataset. The aim is to determine which algorithm provides the highest prediction accuracy.

**Dataset:**
The IRIS dataset is one of the most popular datasets in pattern recognition literature. It consists of three classes IRIS Setosa,IRIS Versicolor and IRIS Virginica of 50 instances each, where each class refers to a type of iris plant. Each instance has four attributes:

        Sepal length
        Sepal width
        Petal length
        Petal width

**Algorithms Compared:**

        1) Decision Trees
        2) Support Vector Machines
        3) k-Nearest Neighbors
        4) Naive Bayes

**Requirements:**
        
        Python 3.x

****Libraries:****
        
         1 scikit-learn
         2 pandas
         3 numpy
         4 matplotlib (for visualization)
         5 Seaborn

**Results:**
        **Algorithm	                     Prediction accuracy**
1) Support Vector machine(SVM):	             97.77%
2) K Nearest Neighbour(KNN):	             95.55% for K=12
3) Decision tree:	                       93.33%
4) Naive bayes:                               93.33%

**Visualizations:**
        During the training and test split, 70% was used for training and 30% for testing purposes.
        30% of 150 is 45. That’s the reason the total support count is 45.

        1) Naive Bayes Algorithm: Depending on the output, among the 45, there are 13 Iris Setosa, 18 Iris 
        Virginica, and 14 Iris Versicolor. The same number has been reflected during the 
        prediction evaluations in the confusion matrix.
        
        2) KNN Algorithm: Depending on the output, among the 45, there are 14 Iris Setosa, 16 Iris 
        Virginica, and 15 Iris Versicolor. The same number has been reflected during the 
        prediction evaluations in the confusion matrix.
        
        3) Decision Tree Algorithm: Depending on the output, among the 45, there are 14 Iris Setosa, 23 Iris 
        Virginica, and 8 Iris Versicolor. The same number has been reflected during the 
        prediction evaluations in the confusion matrix.
        
        4) Support Vector Machines(SVM): Depending on the output, among the 45, there are 15 Iris Setosa, 24 Iris 
        Virginica, and 16 Iris Versicolor. The same number has been reflected during the 
        prediction evaluations in the confusion matrix.

**Conclusion**

Based on the comparative study,Support Vector Machine Algorithm proved to be the most efficient for the IRIS dataset among the four algorithms tested.


