## Tasks

### Task 1: Exploratory Data Analysis (EDA)

(For Questions 1-3) Choose a public dataset. According to your last NIM number, conduct one of the following algorithms:

1. Naïve Bayes
2. k Nearest Neighbor
3. k-Means
4. C4.5
5. Neural Network
6. Logistic Regression
7. FP Growth
8. Fuzzy C-Means
9. Decision Tree
0. Support Vector Machine

Perform Exploratory Data Analysis (EDA) using the Python programming language for the dataset you are using (LO1, 10 points).

### Task 2: Data Splitting and Testing

Divide the percentage of training data, validation, and test data for the dataset. Test the data from the algorithm on the dataset you choose. Use the performance indicator related to your tasks (LO5, 15 points).

### Task 3: Implementation and Analysis

For number 3, do it with 2 tasks, first with the Python program and second one using Rapidminer. Use some screenshots as necessary. Also provide analysis as necessary (LO3, LO4, 25 points).

### Task 4: Neural Network Model

Based on three (3) variables input namely gmat, gpa, and work_experience, you are expected to implement a Neural Network based model that can be employed to assist an admission process in a company where you are working for. The model may be trained, and tested using the following datasets respectively (LO3, LO4, LO5, 15 points)

* Prior to testing the model, make sure the training dataset above is split for training and validation. Please check the performance of the model using CF (confusion matrix) and in accordance to the obtained CF, give your brief evaluation of the model. You are supposed to write the code from scratch in python notebook.

### Task 5: SVM Parameter Calculation

Dataset (data and labels) is given as the following: X = [ [3, 4, -1], [1, 4, -1], [2, 3, -1], [6, -1, 1], [7, -1, 1], [5, -3, 1] ]. Your task is to calculate weight W’s and bias b of the corresponding SVM linear discriminant function f(X) = WT . X + b by using hand-calculation. Make sure your SVM parameters fulfill the following constraints (LO3, LO4, 15 points)

* To confirm whether your calculation result is correct, you may run the similar SVM library provided by python (scikitlearn). Write your code in python notebook \ please

### Task 6: GMM Clustering

Given 2D datasets (UAS_GMM_DATASET.csv) and assuming you do understand the concept of unsupervised learning, please carry out the below tasks as thorough as possible (LO3, LO4, 20 points)
- Find the best possible “k” used for GMM clustering algorithm using silhouette scores.
- After initializing means(i), covariance matrix (i) and phi ), demonstrate how to calculate responsibilities/weights using E-step of the GMM algorithm and the associated log-likelihood.
- Using M-step of the GMM algorithm, now update the values of means, covariance and phi of each cluster
- Go back to B, calculate new responsibilities/weights and new log-likelihood. Check if there is any convergence of the log-likelihood values
- To confirm your results you may need to call the corresponding GMM python library from scikitlearn. Visualize the obtained clusters

