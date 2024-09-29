# Decision Trees and Data Analysis

Decision Trees are a powerful tool in machine learning. They help us make predictions by splitting data into groups.


## Example Dataset

Let's use a simple dataset with two classes, A and B. We have 10 elements, 4 in A and 6 in B.


### Calculating Proportions

We calculate proportions: p_A = 4/10 = 0.4, p_B = 6/10 = 0.6.


#### Entropy and Gini Impurity

Entropy measures uncertainty: 0.971 (moderate disorder). Gini Impurity measures misclassification: 0.48 (some purity).


##### Information Gain

Information Gain measures split effectiveness: 0.0 (no improvement).


###### Decision Tree Example in Python

We'll use Python libraries (pandas, numpy, matplotlib) to analyze the Titanic dataset.


###### Data Preprocessing

We load, clean, and preprocess data: handle missing values, encode categorical variables.


###### Split Data

We split data into training and testing sets (80% training, 20% testing).


###### Train and Evaluate Model

We train a Decision Tree Classifier (entropy criterion) and evaluate its performance using confusion matrix and classification report.


###### Save Decision Tree Model

We save the trained model using export_graphviz for future use.
