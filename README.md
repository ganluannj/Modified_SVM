# Classification of Unbalanced Data with Unequal Cost with Modified SVM 

For binary classification, unbalanced data refer to the data with one class being dominant.
With common classification methods, such as logistic regression, Support Vector Machine
(SVM), the miss classification rate for class with smaller proportion tends to be high. However, there are some scenarios that correct classification of the class with smaller proportion
is crucial, more crucial than correct classification of the class with larger proportion. It is
the case that cost of miss classification of one class is greater than that of the other class
(Unequal cost). Classic classification methods do not work well in these cases. Here in this
course project, I promoted a new group of classification methods based on SVM. In SVM,
training error from both cases are assigned with equal cost. Here in new methods, different
cost is assigned for training error from each class. Two different form of cost function
were promoted in this study. Simulation study were conducted to compare SVM and the
new model based on the total overall loss. New models outperform SVM in simulation
study. Thus the new model works better than SVM in classification of unbalanced data
with unequal cost.

