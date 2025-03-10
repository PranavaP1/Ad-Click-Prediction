##### Models used:
Logistic Regression is incredibly easy to implement and very efficient to train. 

(Logistic Regression implementation is best instead of Linear Regression because the target variable in the dataset is of type categorical, not continuous. So, my dataset is not suitable for linear regression.)
-> After using logistic regression, I have implemented through decision tree classifier, which did not give best accuracy compared to logistic regression.But definitely, both models have shown that they can be very successful in solving classification problems

Decision Tree Classifier
Support vector Classifier(There is no much difference between support vector classifier without kernel and SVC with kernel).
Random Forest Classifier
Neural Networks

### Analysis:
Comparing all the above implementation models, I conclude that Random Forest Algorithm gives the maximum accuracy for determining the click probability. I believe in future there will be fewer ads, but they will be more relevant. And also these ads will cost more and will be worth it.
Accuracy is more for Random Forest than any other models used.
Precision is more for Random Forest which implies more correctness of the model. (implies it has less false positives)
Neural Networks resulted in least accuracy because of some features.

As the data is supervised, PCA is not applicable . As the data which I considered has only 2 classes for prediction, LDA is not supportable due to the below statement: n components cannot be larger than min(n_features, n_classes - 1 ).  So, dimensional analysis is not possible!
