# Artificial-Neural-Networks

We here explore the 'Digits' dataset from the Sci-Kit Learn package.
We show a few properties of this dataset and we then start to train a model to predict the right digits
for each image in the dataset.

We then make two tests:

1)We test for each image if the value of the digit in this image is above or equal to 7.

2)In a second test,we check if the value is an odd number.

After that, we train an instance of KNeighborsClassifier
using those two tests,and we can then perform predicitions: we get a two column matrix, the first
column will return False at a given row if the prediction of the first test is not correct(that is if the value 
is under 7) and True if the number is above 7 or equal to 7.
