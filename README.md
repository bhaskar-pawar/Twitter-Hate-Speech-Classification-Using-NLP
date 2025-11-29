# Twitter-Hate-Speech-Classification-Using-NLP
This project classifies tweets into three categories using Natural Language Processing and Machine Learning:

0 → Hate Speech

1 → Offensive Language

2 → Neutral / Clean Speech

The model is built using TF-IDF for text vectorization and Linear Support Vector Classifier (SVM) for classification. 

## Steps in the Project

- Load and clean text data

- Remove links, mentions and hashtags

- Tokenize text

- Remove stopwords and lemmatize

- Convert text to vectors using TF-IDF

- Split into train and test sets

- Train Linear SVC model

- Evaluate performance

- Predict on custom input text

## Model Performance

Accuracy: ~88%

Best performance on classes 1 (Offensive) and 2 (Neutral)

Class 0 (Hate Speech) is hardest due to fewer real samples
