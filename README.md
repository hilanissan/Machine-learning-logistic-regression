This repository is part of a **Machine Learning** course assignment and demonstrates the application of **Logistic Regression** in classification tasks. It contains two sections, each focusing on different use cases of logistic regression. All datasets used in this exercise can be accessed via the provided link.

## Contents

### 1.1 Part 1: Predicting University Admission
In the first part of this assignment, you'll build a logistic regression model to predict whether a student gets admitted to a university.

#### Problem Description:
As a university administrator, you need to predict each applicant's chance of admission based on their exam scores. You have historical data on previous applicants, including their scores from two exams and the final admission decision (accepted or rejected). Your task is to develop a classification model using **logistic regression** to estimate the probability of admission based on these exam scores.

#### Key Concepts:
- **Logistic Regression**: Logistic regression is a supervised machine learning algorithm used for binary classification problems. Unlike linear regression, logistic regression predicts the probability that a given input belongs to a particular class (in this case, whether a student is admitted or not) by applying the logistic function (also known as the sigmoid function) to the input.
  
#### Tasks:
- Build a logistic regression model using the provided dataset.
- Train the model on the exam scores and admission decisions.
- Use the model to predict the probability of admission for new applicants.

### 1.2 Part 2: Quality Assurance for Microchips
In the second part, you'll implement **regularized logistic regression** to predict whether microchips from a fabrication plant pass quality assurance (QA).

#### Problem Description:
As the product manager of a factory, you need to decide whether microchips should be accepted or rejected based on the results of two tests. The dataset includes test results for microchips and their QA outcome (pass or fail). Using logistic regression with regularization, you will build a classification model to predict the outcome of QA.

#### Key Concepts:
- **Regularized Logistic Regression**: In cases where the dataset may exhibit multicollinearity or overfitting, regularization techniques (such as **L2 regularization**, also called Ridge Regression) are used to penalize large coefficients and keep the model generalizable to new data.

  The cost function for logistic regression with regularization is modified as:


#### Tasks:
- Implement regularized logistic regression using the provided dataset.
- Train the model to predict whether a microchip passes QA based on the test results.
- Apply the model to predict outcomes for new microchips.

## Logistic Regression Overview
Logistic regression is widely used in machine learning for binary classification tasks where the goal is to assign an input to one of two categories. Unlike linear regression, which predicts continuous values, logistic regression predicts probabilities that are then mapped to discrete classes (e.g., 0 or 1, pass or fail, admit or reject). This makes it a key technique for problems like medical diagnoses, spam detection, and in this case, university admissions and microchip quality assurance.

### Why Regularization?
In real-world applications, especially when dealing with many features or complex datasets, overfitting can occur. Regularization helps by constraining the model, ensuring that it captures the underlying patterns without becoming too complex.

### Dataset Access
All datasets required for this assignment can be accessed via [this link](#). Make sure to download the datasets before running the notebooks.

