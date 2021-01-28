# Gaussian-parametric-classification
parametric classification where class densities are assumed to be Gaussian


In this homework, you implement parametric classification where class densities are assumed to be
Gaussian.
You are provided with two dataset files. As their names imply, the training.csv file will be used for
training and the testing.csv file will be used for testing. Each row of the files corresponds to one
instance. You have 90 instances per file. The first column of the row contains the integer value
representing the age of a customer and the categoric value on the second column represents the
label (positive or negative) corresponding to that customer.
You should use the training instances to estimate the parameters, which are the class priors and the
parameters of the Gaussian densities, namely means and variances. You then test the accuracy of
your model both on the training and the test instances unused during training.
1) In the same figure, plot the likelihood and posterior distributions, together with the training and
test data instances. Use different colors/symbols for different distributions and classes.
2) For the following three cases, calculate the thresholds of decisions for minimum expected risk
and report the total loss on both training and test datasets.
a) The loss of a False Positive (assigning a negative instance to the positive class) is 1 and a
False Negative (assigning a positive instance to the negative class) is 1
b) The loss of a False Positive is 2 and a False Negative is 1
c) The loss of a False Positive is 1 and a False Negative is 2
