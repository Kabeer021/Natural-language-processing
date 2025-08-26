# Word Embedding & Semantic Analysis using Word2Vec and WordNet

This project demonstrates the implementation of Word2Vec embeddings from scratch and the exploration of semantic relationships using WordNet. It covers both neural word representation learning and linguistic analysis of word relationships, providing insights into natural language understanding.

Project Overview

Implemented Word2Vec model (Skip-gram with Negative Sampling) from scratch using Python and TensorFlow.

Trained embeddings on a 61MB Wikipedia text dataset, optimizing vocabulary with subsampling and negative sampling for efficiency.

Preprocessed large-scale text data for tokenization, vocabulary building, and frequency filtering.

Conducted semantic analysis using WordNet, exploring synsets and relationships such as:

Hypernyms & Hyponyms

Meronyms & Holonyms

# Key Features

Custom Word2Vec Implementation: Skip-gram architecture with negative sampling.

Text Preprocessing Pipeline: Tokenization, vocabulary creation, subsampling of frequent words.

WordNet Integration: Analyze word relationships and compute semantic similarity.

Evaluation Metrics: Word similarity, analogy tasks.

# Results

Word Embeddings: Learned semantic relationships (e.g., “king - man + woman ≈ queen”).

WordNet Analysis: Extracted and visualized relationships like hypernyms, hyponyms, and computed similarity scores.
