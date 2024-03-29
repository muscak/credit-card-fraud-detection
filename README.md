# Credit Card Fraud Detection 

Credit card fraud can occur when unauthorized users gain access to an individual's credit card information in order to make purchases, other transactions, or open new accounts. A few examples of credit card fraud include account takeover fraud, new account fraud, cloned cards, and cards-not-present schemes. This unauthorized access occurs through phishing, skimming, and information sharing by a user, oftentimes unknowingly. However, this type of fraud can be detected through means of artificial intelligence and machine learning as well as prevented by issuers, institutions, and individual cardholders. According to a 2021 annual report, about 50% of all Americans have experienced a fraudulent charge on their credit or debit cards, and more than one in three credit or debit card holders have experienced fraud multiple times. This amounts to 127 million people in the US that have been victims of credit card theft at least once [1].

This is a binary classification problem which will mark the transactions either as fraudulent or non-fraudulent based on the trained model on the [Kaggle dataset](https://www.kaggle.com/datasets/yashpaloswal/fraud-detection-credit-card). 
During this study, we evaluated the permormance of the below algorithms by using 10 fold cross validation:

1. Logistic Regression (LR)
2. Linear Discriminant Analysis (LDA)
3. $k$-Neighbors Classifier (KNN)
4. Decision Tree Classifier (CART)
5. Gaussian Naive Bayes (GNB) 
6. Support Vector Classifier (SVM) algorithms are evaluated performance-wise.

First we used `RandomUnderSampler` as the dataset was in high imbalanced state. Then we removed the outliers and applied `StandardScaler` to scale the feature. We could achive **98.21%** testing accuracy score with LR after hyper-parameter tuning. 


## References

[1] [Credit card fraud](https://en.wikipedia.org/wiki/Credit_card_fraud)


*Thanks to [flaticon.com](https://www.flaticon.com/) for free icons in the notebook.
