# Machine Learning Resources

<b> Notebooks from the [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook/tree/master):</b>



<b> Notebooks from my university lectures: </b>




[Support_Vector_Machine_Classification](https://github.com/RubyNixx/machine_learning/blob/main/Support_Vector_Machine_Classification.ipynb)

Build a Support Vector Machine that will find the optimal hyperplane that maximizes the margin between two toy data classes using gradient descent.

It's a supervised machine learning algorithm which can be used for both classification or regression problems. But it's usually used for classification. Given 2 or more labeled classes of data, it acts as a discriminative classifier, formally defined by an optimal hyperplane that seperates all the classes. New examples that are then mapped into that same space can then be categorized based on on which side of the gap they fall.

What are Support Vectors?

Support vectors are the data points nearest to the hyperplane, the points of a data set that, if removed, would alter the position of the dividing hyperplane. Because of this, they can be considered the critical elements of a data set, they are what help us build our SVM.

Use cases: Classification, regression (time series prediction, etc) , outlier detection, clustering

As a rule of thumb, SVMs are great for relatively small data sets with fewer outliers.
Other algorithms (Random forests, deep neural networks, etc.) require more data but almost always come up with very robust models.
The decision of which classifier to use depends on your dataset and the general complexity of the problem.
"Premature optimization is the root of all evil (or at least most of it) in programming." - Donald Knuth, CS Professor (Turing award speech 1974)
