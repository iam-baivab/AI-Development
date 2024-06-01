# Supervised Learning: Classification

## Overview
Supervised learning is a type of machine learning where an algorithm is trained on a labeled dataset. This means that the input data is paired with the correct output. The goal is for the algorithm to learn a mapping from inputs to outputs that can be used to predict the output for new, unseen inputs. Classification is a common type of supervised learning where the output variable is categorical, meaning it represents a class label.

<img src="https://cdn.educba.com/academy/wp-content/uploads/2019/09/Explain-Classification-Algorithms-in-Detail.png" height="300">

## Table of Contents
1. [Introduction](#introduction)
2. [Types of Classification](#types-of-classification)
3. [Key Concepts](#key-concepts)
4. [Common Algorithms](#common-algorithms)
5. [Performance Metrics](#performance-metrics)
6. [Applications](#applications)
7. [Example Workflow](#example-workflow)
8. [Conclusion](#conclusion)

## Introduction
Classification tasks aim to assign a category to an input based on its features. For instance, an email can be classified as "spam" or "not spam", or a tumor can be classified as "malignant" or "benign". Supervised learning algorithms build a model that makes these classifications based on examples in the training data.

## Types of Classification
- **Binary Classification**: Classifies inputs into two distinct classes (e.g., spam or not spam).
- **Multiclass Classification**: Classifies inputs into one of three or more classes (e.g., categorizing types of animals).
- **Multilabel Classification**: Each input can belong to multiple classes simultaneously (e.g., tagging a photo with multiple labels like "beach", "sunset", "vacation").

## Key Concepts
- **Training Set**: The dataset used to train the model.
- **Test Set**: The dataset used to evaluate the performance of the model.
- **Features**: The input variables used for making predictions.
- **Labels**: The output variable representing the class of each input.

## Common Algorithms
- **Logistic Regression**: A statistical model that uses a logistic function to model a binary dependent variable.
<img src="https://assets-global.website-files.com/5ced99a4fd5e3ae5e159181c/61a79d95128eb3d804b7ff74_KYdeWR91QVfwv1rRiTj3Yq87_5_mdKRYmfz7GigdVCw2cHyChluQ0g0GQbuyBXUbRdfDcIeXiwSiaHJYvNTO6KrB-4-VEnA1bF0bX-IYBYTLQA--TY8bzmv5plfglQ4b7-f1VLOI.png" height=400>

- **Decision Trees**: A flowchart-like structure where an internal node represents a feature, the branch represents a decision rule, and each leaf represents an outcome.
<img src="https://assets-global.website-files.com/5ced99a4fd5e3ae5e159181c/61a79d958aa2147980a4e5ba_ysXw_BoPMEz7s_Y2sFhYoKwt_h4jmYYQOLbH10ittWAiW32cZkyTf-GoH84Uzy8EgmcFStgYaAEJ9WVvlHPySowrEIoxWkbsPjteBfQQ5aznjLmqg14VX1sTDquq5BzDNPP3oilp.png" height=400>

- **Random Forest**: An ensemble of decision trees, generally trained with the bagging method.
<img src="https://miro.medium.com/v2/resize:fit:1400/1*hmtbIgxoflflJqMJ_UHwXw.jpeg" height=400>

- **Support Vector Machines (SVM)**: A classifier that finds the hyperplane that best separates the classes in the feature space.    
<img src="https://assets-global.website-files.com/5ced99a4fd5e3ae5e159181c/61a79d95e1b9565f171db7cc_o2lFCv5i57fqv_jvJHUexY1yvo0IzUn2ckq5WBx4J2mj1XrAuRHsCJuDRZ4hwqGadG7t2OgYCOwKxLdZHzBJybzeSLkCB-s8MydcmfHy6Apk5ekhzN_DRw1pFRJ6MP5EyRtlElBf.png" height=400>

- **k-Nearest Neighbors (k-NN)**: Classifies a data point based on how its neighbors are classified.
<img src="https://assets-global.website-files.com/5ced99a4fd5e3ae5e159181c/61a79d95db8073623e1430a4_XjsuvXUtXYqTinwu3RPayQ0bIn84XQwR2wShJZElx9_vh9oPky-qX4L_VWgh-rcvsbfux2qaWMCr-4jxgQlKtsS6jwyE1na_vir7N39TggeZi38_tUV1u5Xv2GLzPRhevOTMykaP.png" height=400>

- **Naive Bayes**: A probabilistic classifier based on Bayes' theorem with strong independence assumptions.

- **Neural Networks**: Consist of layers of neurons that can learn complex patterns in data.

## Performance Metrics
- **Accuracy**: The ratio of correctly predicted instances to the total instances.
- **Precision**: The ratio of true positive predictions to the total positive predictions.
- **Recall (Sensitivity)**: The ratio of true positive predictions to the actual positives.
- **F1 Score**: The harmonic mean of precision and recall.
- **ROC-AUC**: The area under the receiver operating characteristic curve, a measure of the model's ability to distinguish between classes.

## Applications
- **Spam Detection**: Classifying emails as spam or not.
- **Image Recognition**: Identifying objects or features in images.
- **Medical Diagnosis**: Classifying medical images or symptoms to diagnose diseases.
- **Sentiment Analysis**: Determining the sentiment of a piece of text.
- **Fraud Detection**: Identifying fraudulent transactions or activities.

## Example Workflow
1. **Data Collection**: Gather the dataset, ensuring it has labeled examples.
2. **Data Preprocessing**: Clean the data, handle missing values, and perform feature scaling.
3. **Train-Test Split**: Split the dataset into training and testing sets.
4. **Model Selection**: Choose an appropriate classification algorithm.
5. **Training**: Train the model on the training data.
6. **Evaluation**: Evaluate the model on the test data using performance metrics.
7. **Hyperparameter Tuning**: Adjust the model parameters to improve performance.
8. **Prediction**: Use the trained model to classify new data.

## Conclusion
Supervised classification is a fundamental aspect of machine learning, enabling the development of systems that can make informed predictions and decisions. By understanding the key concepts, algorithms, and applications, one can effectively leverage classification techniques in various domains to solve real-world problems.