# Naive-Bayes-Supervised-Method

This is a simple probabilistic classifier based on applying Bayes' theorem with strong (naive) independence assumptions between the features 
It is a classification technique based on Bayes’ Theorem with an assumption of independence among predictors. In simple terms, a Naive Bayes classifier assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature. For example, a fruit may be considered to be an apple if it is red, round, and about 3 inches in diameter. Even if these features depend on each other or upon the existence of the other features, all of these properties independently contribute to the probability that this fruit is an apple and that is why it is known as ‘Naive’

### HOW IT WORKS 
Bayes theorem provides a way of calculating posterior probability P(c|x) from P(c), P(x) and P(x|c). Look at the equation below
 P(c|x) = (P(x|c)* P(c)) /  P(x) 
Above,
P(c|x) is the posterior probability of class (c, target) given predictor (x, attributes).
P(c) is the prior probability of class.
P(x|c) is the likelihood which is the probability of predictor given class.
P(x) is the prior probability of predictor.

 Now, use Naive Bayesian equation to calculate the posterior probability for each class. The class with the highest posterior probability is the outcome of prediction.
 
### USE CASES OF NAIVE BAYES 
1. categorizing news 
2. email spam detection
3. face recognition
4. Medical diagnosis
5. digit recognition
6. weather prediction
7. sentimenty analysis


### ADVANTAGES OF NAIVE BAYES CLASSIFIER 
1. Very simple and easy to implement
2. Need less training data 
3. Handles both continuous and discrete data 
4. Highly scalable with number of predictors and data points
5. At it is fast, it can be used in real time predictions
6. Not sensitive to irrelevant features
7. It also perform well in multi class prediction
8. It perform well in case of categorical input variables compared to numerical variable(s)

### DISADVANTAGES OF NAIVE BAYES CLASSIFIER 
1. Another limitation of Naive Bayes is the assumption of independent predictors. In real life, it is almost impossible that we get a set of predictors which are completely independent.

### THREE TYPES OF NAIVE BAYES IN SCIKIT LEARNING
1. Gaussian: It is used in classification and it assumes that features follow a normal distribution.

2. Multinomial: It is used for discrete counts. For example, let’s say,  we have a text classification problem. Here we can consider bernoulli trials which is one step further and instead of “word occurring in the document”, we have “count how often word occurs in the document”, you can think of it as “number of times outcome number x_i is observed over the n trials”.

3. Bernoulli: The binomial model is useful if your feature vectors are binary (i.e. zeros and ones). One application would be text classification with ‘bag of words’ model where the 1s & 0s are “word occurs in the document” and “word does not occur in the document” respectively.
