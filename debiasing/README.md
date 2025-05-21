
# Operations on Word Vectors

## Introduction

Word embeddings are a foundational technology in modern Natural Language Processing (NLP). Unlike traditional one-hot representations, word embeddings such as GloVe and Word2Vec capture rich semantic relationships between words in a dense, continuous vector space. This enables algorithms to understand word similarities, analogies, and even subtle relationships, powering many state-of-the-art NLP applications—from search and recommendation systems to chatbots and machine translation. Understanding and working with word embeddings is a key skill for any machine learning or NLP practitioner.

## Project Overview

This project demonstrates practical techniques for working with pre-trained word embeddings (GloVe) in Natural Language Processing. The notebook covers essential operations such as measuring word similarity, solving analogy tasks, and reducing gender bias in word vectors.

## Features

- Loading and exploring pre-trained GloVe embeddings
- Computing cosine similarity between word vectors
- Solving word analogy problems using vector arithmetic
- Applying debiasing techniques to mitigate gender bias in embeddings

## Getting Started

1. **Download GloVe Embeddings**  
   Download the [GloVe word vectors](https://nlp.stanford.edu/data/glove.6B.zip), unzip the archive, and place the file `glove.6B.50d.txt` in the `data/` directory.

2. **Install Dependencies**  
   Required packages: `numpy`, `jupyter`.  
   Install via pip if needed:
   ```bash
   pip install numpy jupyter
   ```

3. **Run the Notebook**
   ```bash
   jupyter notebook Operations_on_word_vectors_PROD.ipynb
   ```

## Example Usage

- Compute the similarity between words like **"man"** and **"woman"**
- Find the best word to complete analogies such as **"man" is to "woman" as "king" is to "queen"**
- Reduce gender bias in word embeddings with debiasing functions

## Author

The project idea and overall assignment structure are based on the Deep Learning Specialization (Coursera, by Andrew Ng), but the code solution and implementation details are my own and have been modified and improved for this repository.

