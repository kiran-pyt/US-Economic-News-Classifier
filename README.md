# US-Economic-News-Classifier

In this project, I developed a classifier to categorize US economic news articles into relevant and non-relevant groups. Using Python, I employed various natural language processing (NLP) techniques and machine learning algorithms to achieve this goal

Overview
The project involved several key steps:

**Data Preprocessing:**
Initially, I cleaned and prepared the dataset by removing irrelevant data and HTML tags. I also eliminated URLs, punctuations, digits, and stopwords from the text, and applied lemmatization to normalize the text data.

**Feature Extraction:** 
I utilized TF-IDF vectorization, a common technique in NLP, to convert the text data into numerical features. Additionally, I experimented with Count Vectorization and Hashing Vectorization for comparison purposes.

**Model Training and Evaluation:** I trained a Gaussian Naive Bayes classifier on the TF-IDF vectorized data. Subsequently, I evaluated the model's performance on both training and testing datasets. Visualizations such as confusion matrices were used to interpret the classification results


**Results**
The classifier provided valuable insights, including training and testing accuracy scores, classification reports with precision, recall, and F1-score for both relevant and non-relevant categories, and visual representations of confusion matrices to understand the model's performance.

![image](https://github.com/kiran-pyt/US-Economic-News-Classifier/assets/120393460/fffe37e2-13a2-47ff-95df-5fa7cd4c5a53)






