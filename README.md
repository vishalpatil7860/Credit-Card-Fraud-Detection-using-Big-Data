# Credit-Card-Fraud-Detection-using-Big-Data
We trained and compared the performance of five different machine learning algorithms: logistic regression, decision tree classifier, random forest classifier, artificial neural network, and gradient boosting.

We found that the Random Forest classification performed the best, achieving an impressive 99.96% accuracy on our test set. This indicates that our proposed system has the potential to effectively detect fraudulent credit card transactions.


Introduction

Over the past few years credit card frauds have increased , this happens to be one of the most critical threats that have affected not only individuals but also companies. Many E-commerce and online sites have increased the modes of online payments , but this also comes with the cost of increasing fraud transactions.
The main aim of this project is to Build a Credit Card Fraud Detection system using the transaction details in Python using Machine learning algorithms, we use 5 different types of algorithms to identify fraud transactions in a given dataset.
The 5 algorithms we use are : Logistic Regression , Decision Tree classification , Gradient boosting , Random Forest, and Artificial Neural network. We then do a comparison between all the models to understand which algorithm works best and gives us the highest accuracy results.


Motivation:

Credit card fraud is a major problem in the financial industry, costing billions of dollars each year. It is important to develop effective methods to detect and prevent fraud in order to protect customers and businesses from financial losses.
Description of the Problem:
The goal of this project is to develop a system for detecting credit card fraud using machine learning algorithms. The system will be able to identify fraudulent transactions by analyzing the data associated with each transaction, such as the amount, merchant, and customer information.


Idea:

The proposed methodology will use five different machine learning algorithms to detect credit card fraud. The algorithms will be trained on a dataset of historical transactions and will be used to identify suspicious transactions in real-time. The system will also be able to detect patterns in the data that may indicate fraudulent activity. The system can be used to alert customers and businesses when suspicious activity is detected, allowing them to take appropriate actions.


Related work

Previous approaches to credit card fraud detection using machine learning algorithms have included the use of supervised learning algorithms such as logistic regression, decision trees, and support vector machines. Unsupervised learning algorithms such as clustering and anomaly detection have also been used. Other approaches have included the use of neural networks, genetic algorithms, and ensemble methods. Additionally, various data mining techniques such as association rule mining, sequential pattern mining, and outlier detection have been used to detect fraudulent transactions.


Methodology

(a) Logistic regression

• Logistic regression is one of the machine learning methods used for classification
• The approach selected here is binary logistic regression as the feature ‘Class’ has two values (0 = not fraudulent, 1= fraudulent)
• Two logistic regression models are created. One is the full model which has all the features and the other is a partial model which omits non-correlated features.
• The two models are compared based on various metrics such as precision, recall, f1-score & ROC

(b) Decision Tree Classifier

• Decision tree classifier is a supervised learning algorithm used for classification tasks. It works by creating a tree-like structure of decisions and their possible consequences, including the prediction of a target value.
• The decision tree classifier is based on the concept of entropy and information gain.
• It works by splitting the data into smaller subsets based on the most significant attribute or feature, and then making predictions based on each subset with a maximum depth of 3.h
• The model here is evaluated using precision, recall, f1-score, support, and confusion matrix.

(c) Random Forest Classification

• Random forest is a classification algorithm , this algorithm uses multiple decision trees throughout the process. In simpler terms , it combines the output of multiple decision trees is uses and then gives a single result based on them.
• This algorithm has 3 main hyperparameters that are used or that are to be set before we train our model , namely : Node size , the number of featured sample and the number of trees.
• This algorithm reduces the risk of overfitting & provides flexibility. However, it this in comparison requires more time (time-consuming process) and is a complex algorithm.
• The metrics used for comparison are – recall , f1-score, and confusion matrix.

(d) Gradient Boosting Classifier

• Gradient Boosting is a technique used in regression and classification analysis; it is also considered to be one of the most powerful techniques used in predictive modeling.
• Gradient boosting involves 3 elements that are used : A loss function(for optimization) , a weak learning function (for predictions) and additive model(this is to add weak learners and help minimize the loss function)
• It also helps minimize the overall prediction error .
• The model used in this algorithm is evaluated using precision , recall , confusion matrix and f1-score

(e) Artificial Neural Network

• ANN is computational model that mimics the way the human brain nerve cells work. This algorithm uses the learning algorithms in order to independently adjust.
• ANN models use a network of layers , the first layer is the input layer (neurons) , this layer then further sends data to the deeper layers , which then gives the final output
• ANN takes data samples rather than the entire
