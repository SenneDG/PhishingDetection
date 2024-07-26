# SMS Smishing Detection using Machine Learning
This project was made as a part of the Machine Learning Course of Group T, KU Leuven

### Project Overview
This project focuses on detecting SMS smishing (SMS phishing) using machine learning techniques. Smishing involves fraudulent text messages that trick recipients into revealing sensitive information or installing malware. Our goal is to accurately classify SMS messages as ham (legitimate), spam, or smishing.

### Dataset
We used the "SMS Phishing Dataset for Machine Learning and Pattern Recognition", which contains labeled SMS messages for smishing detection. The dataset includes features like SMS body text, and indicators for the presence of URLs, emails, and phone numbers.

### Preprocessing
The preprocessing steps included:

- Tokenization
- Stopword Removal
- Lemmatization
- Feature Extraction (e.g., presence of URLs, emails, phone numbers)

### Models
We evaluated the following machine learning models:

- Support Vector Machines (SVM)
- Random Forest Classifier (RFC)
- Naive Bayes
- Neural Networks

### Evaluation Metrics
The models were assessed using:

- Accuracy
- Receiver Operating Characteristic Area Under the Curve (ROC AUC)

### Results
The SVM with RBF kernel and the Random Forest Classifier showed superior performance in classifying SMS messages, achieving high accuracy and AUC scores.
