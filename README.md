# Disaster Detection NLP Text Classification

This project focuses on classifying tweets as disaster-related or not using Natural Language Processing (NLP) techniques. The dataset is preprocessed, vectorized, and used to train machine learning models for classification.

## Features

- Text preprocessing: punctuation removal, stopword removal, lemmatization.
- Vectorization using TF-IDF and Word2Vec.
- Classification using Logistic Regression and Naive Bayes.
- Performance evaluation using metrics like AUC, confusion matrix, and classification report.

## Dataset

The project uses the following datasets:

- `data/train.csv`: Training data containing tweets and their labels.
- `data/test.csv`: Test data for predictions.
- `data/sample_submission.csv`: Sample submission format.

## Installation

1. Clone the repository.
2. Install the required Python packages using the `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the `DisasterDetection.ipynb` notebook.
2. Follow the steps in the notebook to preprocess the data, train models, and evaluate performance.
3. Use the trained model to predict disaster-related tweets in the test dataset.

## Enhancements

You can improve the model by:

- Using advanced classification algorithms like SVM, XGBoost, or neural networks.
- Tuning hyperparameters using GridSearch.
- Employing advanced word embedding techniques like GloVe or BERT.

## Results

The notebook provides detailed performance metrics for the models, including AUC scores and confusion matrices.
