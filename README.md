Arabic News Topic Classification

Overview

This project classifies Arabic news articles into different topics using word embeddings (Word2Vec and FastText) and a Random Forest classifier. The dataset contains Arabic news articles labeled with topics such as Science & Technology, Sports, Business & Economy, Politics & Society, Culture & Arts, News & General, and Lifestyle & Entertainment.

Features

Preprocessing: Tokenization, stopword removal, normalization, and text cleaning.

Word Embeddings: Word2Vec and FastText for feature representation.

Classification: Random Forest for multi-class classification.

Evaluation: Accuracy, precision, recall, and F1-score to assess model performance.

Dataset

The dataset consists of Arabic news articles with the following columns:

Title: The title of the news article.

Topic: The topic category (target variable).

Article_content: The full text of the article.

Installation

To run this project, install the required dependencies:

pip install pandas numpy scikit-learn gensim arabicstopwords nltk

Usage

Preprocess the data:

Clean and normalize Arabic text.

Train Word2Vec or FastText embeddings.

Train the classifier:

Extract word vectors for each article.

Train a Random Forest model on the feature vectors.

Evaluate the model:

Compute accuracy, precision, recall, and F1-score.

Run the script:

python main.py

Results

Word2Vec and FastText embeddings were tested.

Random Forest achieved high accuracy on topic classification.

Future Improvements

Experiment with deep learning models like BERT for better accuracy.

Use additional preprocessing techniques to enhance text representation.

License

This project is open-source and available under the MIT License.
