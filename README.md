# Everlytics-ML-project

Building a Random Forest Classifer model to predict Phising Website

Approach:

1.Business problem:

This is Phising website prediction. Majority of the products are going to malware detects because of phising website thereby losing important transactional information,payment information and personal information so we are designing a product for $X dollar price as it detects phising website or not.

2.Constraints:

Low Latency constraints
Misclassification rate is heavy

3.Business metrics

Confusion matrix
F1 score

4.Machine Learning Formulation

It is binary classification problem.

5.Feature engineering

Dataset contains domain based features and feature engineering already done for all most all features

6.Random classifier model

Based on the model We use random classifer because features are less so tree based model works well for low dimentioanlity data and feature importance we get using gini impurity to know what features giving good results

7.Results

SSBfinal_State and URl_Anchor feature contributed most to the prediction.

Web traffic and prefix-suffix features also good to make predictions.

We are getting Test F1 score of about 92.2% in the random forest classifier.

We think Increasing true positives and decresing false negative is importanct in this model because this is for cyber security probelm so considering both precision and recall as metrics there by calculating F1 score will give some intuition of our model.

