# Email Spam Filtering using Naive Bayes
This project aims to build an email spam classifier using the Naive Bayes algorithm. The classifier analyzes the content of emails and predicts whether they are spam or non-spam (ham).

## Dataset
The [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) used for training and evaluation can be obtained from Kaggle. 
The dataset should consist of labeled emails, with each email tagged as spam or ham.

Ensure that the dataset is in the appropriate format, such as a CSV file, and stored in a directory accessible to the project. Update the file path in the Python code accordingly.

## Dependencies
This project requires the following dependencies:

- pandas: A powerful data manipulation library for data analysis. It is used to load and preprocess the dataset.
- nltk: The Natural Language Toolkit provides essential tools and resources for natural language processing. It is used for stopword removal.
- scikit-learn: A popular machine learning library that provides a wide range of algorithms and evaluation metrics. It is used for training the Naive Bayes classifier and evaluating its performance.
