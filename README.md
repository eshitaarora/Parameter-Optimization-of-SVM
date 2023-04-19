# Parameter Optimization of SVM
## What is SVM and Parameter Optimization?
Support Vector Machine (SVM) is a widely used supervised learning algorithm that is particularly useful for solving classification problems in Machine Learning. SVM's accuracy can be improved by adjusting its key parameters such as kernel, C, and gamma, a process referred to as hyperparameter tuning.

One common approach for hyperparameter tuning is to use GridSearchCV, which is a built-in function in the scikit-learn library of Python. GridSearchCV can be used to search for the best combination of parameter values that optimize SVM's performance.

In this Python file, I have used fitness function to optimize the SVM parameters. The fitness function takes in the SVM parameters, trains the model on the training data, and evaluates its accuracy on the validation set. The optimization algorithm can then be used to find the optimal values for the parameters that maximize the fitness function.
# Dataset downloaded from UCI library
https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients

This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005. 
It consists of 30,000 instances and 24 attributes, including the target variable "default payment next month". The dataset is used for predicting the likelihood of default payments by credit card clients.

Number of Rows:30,000
Number of columns:25
# Convergence Graph
![image](https://user-images.githubusercontent.com/78889909/233208070-7435a669-f53a-4685-ae1b-488b69f9b822.png)

# Conclusions
Based on the above graph, it can be inferred that the model is well-trained and the parameters have been effectively optimized, as evidenced by the small gap between the training and cross-validation curves. This graph corresponds to the sample with the best accuracy, which is Sample 2 with an accuracy of 0.78. The optimal hyperparameters for this sample are a rbf kernel, Nu value of 3.83, and an Epsilon value of 6.83.
