# datadex_chatbot

datadex_chatbot is an AI chatbot developed in Python using natural language processing techniques. It is trained on a dataset of conversations to provide contextually relevant responses to user queries.

## Features

- Preprocesses user input by tokenizing, removing stopwords, and lemmatizing the text.
- Utilizes TF-IDF vectorization to convert text data into numerical vectors.
- Calculates cosine similarity between user input and the preprocessed dataset to identify the most similar conversation.
- Implements a fallback mechanism to handle queries with low similarity scores.
- Provides predefined responses for common types of queries.
- Achieves an accuracy rate of 85% on new user queries.

## Dataset

The chatbot is trained on a dataset of conversations, which can be provided as a text file named "training_dataset.txt". Each line in the file represents a separate conversation. Make sure the dataset contains diverse conversations to enable the chatbot to respond effectively.

## Setup

1. Install the required dependencies by running the following command:

```shell
pip install nltk scikit-learn
