# Suport vector machine SVM

- One of the best classifiers ever, which was the dominant algorithm for many years before ANN.

- works with linear & non-linear classification. Also, can be used for regression task, and outliers detection.

- Classification can be binary or multi class. 

- we post each data item as a point in n-dimensional space (where n is the number of feature you have ), with the value of each Feature being the value of a particular coordinator. Then , we perform classification by finding the optional hyper-plane that differentiates the two classes very well 


- How SVM work :

- The main ideas about choosing the best hyperplane that maximizes the margins between classes.
- Support vectors : the closest that identify the best hyperplane 
- The sum algorithm has a Feature to ignore outliers and find the hyper-plane that has the maximum margin. 

- Kernal trick:

- The sum kernel is a function that takes low dimensional input space and transforms it to a higher dimensional space.
- it convert not separable problem to separation problems.
- it is mostly useful in non-linear data separation problem.
- Simply putt does some extremely data transformations, then finds out the process to separate the data based on the labels or outputs you’ve defined. 

- Pros 

1- One of the simplest machine learning algorithms yet provides great efficiency 
2- It can also used for feature extraction.
3- Logistic models can be updated easily with new data using stochastic gradient descent.

- Cons 
1-  It requires Transformation of non-linear features.
2- They are not fixible enough to naturally capture more complex relationships.

  




