---
title: 'Dense vs. Sparse Vectors'
tags: [Vector Representation, Machine Learning, NLP]
---
## Core Idea
Dense and sparse vectors are two types of data representations, with dense vectors having mostly non-zero values and sparse vectors having mostly zero values.

## Explanation
In vector-based data representation, **dense vectors** are filled with non-zero values, making them compact and efficient for high-dimensional data. **Sparse vectors**, by contrast, contain mostly zero values and are useful for representing large, sparse data, like word counts in text documents. Dense vectors are commonly used in embeddings due to their efficiency, while sparse vectors are often used for simpler, memory-conserving applications.

## Applications/Use Cases
- **Embeddings** – Typically use dense vectors to represent word or sentence meanings compactly.
- **Text Classification** – Sparse vectors may represent words in a document for simpler classification models.
- **Information Retrieval** – Uses sparse representations like TF-IDF to match search queries with documents.

## Related Resources
- **“Efficient Estimation of Word Representations in Vector Space” by Mikolov et al.** – Describes the use of dense vectors in embeddings.
- **“Introduction to Information Retrieval” by Manning, Raghavan, and Schütze** – Covers sparse vector applications in search and information retrieval.

## Related People
- **Tomas Mikolov** – Advanced the use of dense vector embeddings with Word2Vec, which replaced traditional sparse representations.

## Related Concepts
- [[Cosine Similarity]] – Commonly used to measure similarity between dense vectors.
- [[Embedding]] – Dense vectors are a common form for embeddings in NLP.
- [[t-SNE]] – Visualizes high-dimensional data, often dense vectors, in a reduced dimensional space.
