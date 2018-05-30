# ML-from-scratch
Several Machine Learning algorithms written using only **numpy**, **pandas**, and **matplotlib**.

## KNN
The K nearest neighbors algorithm written to calculate only Euclidean distance. It is tested on the Iris dataset and compared to the results of the KNeighborsClassifier from sklearn. The results are identicle.

## PCA

The Principal Components Analysis algorithm. It is tested on the MNIST dataset and compared to the results received from PCA from sklearn.decomposition. The results are identical.

## Logistic Regression
Logistic Regression for two classes. It is tested on two randomly generated blobs. The visualization of the decision boundary shows that the algorithm splits the data correctly. The graphs of loss and accuraccy show that the gradient descent algorithm properly minimizes the error.

## Multinomial Logistic Regression
Logistic Regression for three (or more) classes. It is tested on three randomly generated blobs. The visualization of the decision boundary shows that the algorithm splits the data correctly, using a one-vs-rest technique. The graphs of loss and accuraccy show that the gradient descent algorithm properly minimizes the error.