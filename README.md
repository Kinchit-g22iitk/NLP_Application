# Sentence Embedding and Summarization with Faiss and Facebook BERT

This repository contains code for a text processing pipeline that tokenizes text using the NLTK library, applies Sentence Bert embeddings to capture contextual meaning, uses Faiss to find similar sentences related to a provided query, and summarizes these sentences using the Facebook BERT model.

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

In this project, I have implemented a text processing pipeline that consists of the following steps:

1. **Tokenization:** I use the NLTK library to tokenize input text into sentences.

2. **Embedding:** I apply the Sentence Bert embedding technique to capture the contextual meaning of sentences.

3. **Similarity Search:** I utilize the Faiss technique to efficiently find sentences similar to a provided query based on their embeddings.

4. **Summarization:** I summarize the similar sentences using the Facebook BERT model to generate concise and meaningful summaries.

## Requirements

- Python 3.x
- NLTK
- Sentence Bert
- Faiss
- Hugging Face Transformers (for Facebook BERT)

You can install these dependencies using pip.

## Usage

Follow these steps to use the project:

1. **Step 1**: Provide input text that you want to process.

2. **Step 2**: Run the tokenization, embedding, similarity search, and summarization functions provided in the code.

3. **Step 3**: Obtain the summarized output.




