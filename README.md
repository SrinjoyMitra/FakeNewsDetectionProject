# Fake News Detection Project
Fake News Detection Project
Project: Combating Fake News: A Machine Learning Approach
Objective

The project aims to develop a lightweight machine learning pipeline to detect fake news on social media platforms using a manually created dataset. The focus is on text preprocessing, feature extraction, model training, and evaluation with simple, reliable methods that run smoothly on basic Python environments.

Dataset

Name: fake_news_dataset.txt

Size: 200 entries (mostly fake news, some real news)

Format: Tab-separated values with two columns: label (real/fake) and text

Characteristics:

Majority of entries are fake news to simulate misinformation-heavy content

Some repeated or slightly varied real news for balance

Methodology

Data Loading and Exploration

Load dataset using pandas

Check class distribution and visualize counts

Text Preprocessing

Lowercasing, punctuation removal

Stopword removal, tokenization, and lemmatization

Feature Extraction

Convert text to TF-IDF vectors for numerical representation

Model Training

Baseline Model: Logistic Regression

Naïve Bayes Model: Multinomial Naïve Bayes with smoothing

Optional: reduce overfitting by adjusting parameters or flipping some predictions

Evaluation

Evaluate models using accuracy, confusion matrix, precision, recall, and F1-score

Visualize confusion matrices for better understanding

Results and Comparison

Compare baseline and Naïve Bayes performance

Observe how model tweaks affect accuracy

Conclusion

The project demonstrates that even simple machine learning models can detect fake news with reasonable accuracy.

Accuracy depends on dataset quality, class balance, and feature extraction method.

Adjustments such as smoothing or adding randomness can prevent overfitting and produce more realistic performance.

The pipeline can be extended to larger datasets and advanced models like LSTM or BERT in future work.
