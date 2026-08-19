# Arabic Dialect Identification with NLP & Pre-trained Word Embeddings

An NLP project focused on identifying Arabic dialects from text using classical machine learning and neural network approaches.

The project explores Arabic text preprocessing, TF-IDF representations, neural text classification, and pre-trained Arabic FastText word embeddings. Multiple modeling approaches were evaluated using validation and test metrics.

## Project Overview

Arabic dialects share many linguistic characteristics while also exhibiting significant differences in vocabulary, morphology, and writing patterns.

The goal of this project was to investigate machine learning and deep learning approaches for Arabic dialect identification and compare the effect of different text representations and preprocessing techniques.

## Key Components

- Arabic text preprocessing and normalization
- Arabic tokenization using CAMeL Tools
- Arabic stemming and text cleaning
- TF-IDF feature representation
- Multinomial Naive Bayes classification
- Deep Neural Network (DNN) classification
- Convolutional Neural Network (CNN) text classification
- Trainable word embeddings
- Pre-trained Arabic FastText embeddings
- Embedding matrix construction
- Embedding visualization using PCA and t-SNE
- Model evaluation using Accuracy and F1-score
- Vocabulary and out-of-vocabulary (OOV) analysis

## Methodology

### 1. Text Preprocessing

The project experimented with several Arabic text preprocessing operations, including:

- whitespace normalization
- removal of repeated sequences
- removal of numbers
- removal of diacritics
- stop-word removal
- Arabic stemming
- Arabic word tokenization

CAMeL Tools was used for Arabic tokenization.

### 2. Classical Machine Learning

TF-IDF was used to convert Arabic text into numerical feature representations.

A Multinomial Naive Bayes classifier was then trained and evaluated using validation and test datasets.

### 3. Deep Learning

Neural approaches were explored using:

- Dense Neural Networks
- CNN-based text classification
- trainable embedding layers
- frozen pre-trained embedding layers

### 4. Arabic Word Embeddings

A pre-trained 300-dimensional Arabic FastText model was used to construct word embedding representations.

The project also examined vocabulary coverage and out-of-vocabulary words.

### 5. Embedding Visualization

Embedding representations were projected into two dimensions using:

- PCA
- t-SNE

These visualizations were used to explore relationships between word representations and Arabic dialect groups.

## Evaluation

Models were evaluated using:

- Accuracy
- Weighted F1-score
- Validation performance
- Test performance

The project compared different preprocessing strategies and model architectures to investigate their impact on Arabic dialect classification.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- CAMeL Tools
- FastText
- Matplotlib
- Seaborn

## Project Structure

```text
arabic-dialect-identification-nlp/
│
├── notebooks/
│   └── arabic_dialect_identification.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
Notes

The original datasets and large pre-trained embedding files are not included in this repository because of their size and/or distribution restrictions.

The notebook contains the preprocessing, modeling, evaluation, and embedding-analysis workflow used in the project.

Author

Jad Milad Yazji

GitHub: https://github.com/jado30
