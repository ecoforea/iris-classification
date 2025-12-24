# iris-classification: logistic regression vs decision tree 
a. Logistic regression (97.7% accuracy) outperforms Decision Tree (93.3%) by correctly classifying 44/45 vs 42/45 test samples. 
Logistic regression generalise better due to its linear decision boundary being more stable and less prone to overfitting on this small dataset. 
b. Versicolor and virginica are the classes exclusively confused. 
This confusion occurs because both of these flowers share overlapping sepal measurements in the 4-6 cm length range with impact on decision boundary.
c. Use k-fold cross validation to get a robust, less biased model performance with limited data. 
