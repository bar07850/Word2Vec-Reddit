# Reddit Comment Word Embeddings with Word2Vec

This project builds word embeddings from Reddit comments using the Word2Vec algorithm.  
The dataset contains 1 million comments from 40 subreddits, making it an excellent source for natural language processing (NLP) experiments on real-world social media data.

## 📋 Project Overview

The goal of this project is to:
- Download a large Reddit dataset from Kaggle
- Clean and preprocess the text data
- Tokenize the text into words
- Train a Word2Vec model to generate word embeddings
- Explore word similarities based on the learned embeddings

This project demonstrates a full NLP pipeline from raw text to usable vector representations of words.

## 📦 Dataset

- **Dataset:** 1 Million Reddit Comments from 40 Subreddits  
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/smagnan/1-million-reddit-comments-from-40-subreddits)
- **Size:** ~1 million comments
- **Format:** CSV file with subreddit labels and comment text

## 🛠️ Methodology

### Data Download
- Used `kagglehub` to download the dataset programmatically.

### Data Preprocessing
- Removed URLs, special characters, and numbers
- Lowercased all text
- Tokenized comments into word lists

### Model Training
- (Next step) Train a `Word2Vec` model on the tokenized Reddit comments using `gensim`
- Explore word similarities and nearest neighbors

### Example Use Cases
- Finding similar words or slang used across Reddit subcultures
- Visualizing word relationships and clusters

## 💻 How to Run

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/reddit-word2vec-nlp.git
cd reddit-word2vec-nlp
