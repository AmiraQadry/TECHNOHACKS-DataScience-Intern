# Credit Card Fraud Detection 💳
![](https://github.com/luisosorio3214/Credit-Card-Fraud-Detection-/raw/main/Static/credit-card-fraud-detection.png)
## Problem statement
The Problem statement for this project is to use machine learning models [GradientBoostingClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html) to detect 
fraudulent credit card transactions.

## Dataset
In September 2013, during the course of two days, European cardholders conducted credit card transactions that are part of the data collection. 492 fraudulent transactions out of a total of 284807 transactions. 
With the positive class (frauds) accounting for 0.172% of all transactions, this data set is seriously out of balance. In order to ensure secrecy, 
the [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data) dataset has also been adjusted using Principal Component Analysis (PCA). 
All other features (V1, V2, V3, up to V28) are main components generated using PCA, with the exception of "time" and "amount." 
The seconds that passed between the initial transaction in the data set and the succeeding transactions are contained in the feature "time." The transaction amount is the feature's 'amount'.
The feature 'class' represents class labelling, and it takes the value 1 in cases of fraud and 0 in others.
The [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data) dataset needs to be treated since it is so severely unbalanced before a model can be built.

## Overview of the business issue
Retaining highly lucrative clients is often a bank's top priority in terms of commercial objectives. But for several institutions, banking fraud represents a serious danger to achieving this objective. 
This is a problematic situation for both banks and customers in terms of significant financial losses, trust, and reputation.
According to the Nilson Report, global banking scams are expected to reach $30 billion by 2020. 
The number of fraudulent transactions is rising as a result of the expansion of digital payment channels in new and inventive methods.
Machine learning-based credit card fraud detection in the banking sector is not just a trend, but also a requirement for them to set up proactive monitoring and fraud protection procedures.

## Recognizing and Classifying Fraud
Any dishonest act or behavior used to get information without the account holder's authorized consent in order to benefit financially is referred to as credit card fraud. 
The most popular kind of fraud, known as "skimming," is the process of copying the data on a credit card's magnetic strip. Other than this, the other methods include:

- Changing or manipulating real cards
- The production of fake cards
- Telemarketing fraud -Lost or stolen credit cards

## Data Preprocessing
Handling Data Imbalance: I used [RandomUnderSampler](https://imbalanced-learn.org/stable/references/generated/imblearn.under_sampling.RandomUnderSampler.html) for balancing the dataset.
