The Nigeria Language identifier project is my 3MTT Capestone project in NextGen AI & Machine Learning programme. it involves cleaning a dataset and training a model that identify 4 Nigeria languages ( English, Hausa, Igbo and Yoruba) .In this project, i pulled data from AfroFinChain Multilingual and Bible verses.

**Objectives**
Detect Nigerian languages from short text,
Build a text classification model,
Evaluate model performance,
Develop a simple interface for testing new sentences.

**Methodology**
Data Collection,
Data Cleaning,
Exploratory Data Analysis.
Train/Test Split,
TF-IDF Vectorization,
Multinomial Naive Bayes,
Prediction,
Evaluation.


Using Scikit-Learn, i transformed the raw text into numerical feature matrix and trained a Multinomial Naive bayes probability model to classify input language with more than 99% accuracy

The Multinomial Naive Bayes classifier achieved an accuracy of 99.77% on the test dataset containing 1,310 samples. The classification report showed very high precision, recall, and F1-scores across English, Hausa, Igbo, and Yoruba. The confusion matrix showed that 1,307 samples were correctly classified, while only 3 Hausa samples were incorrectly classified as English. No misclassification was observed for Igbo or Yoruba samples.
