# TF-IDF-Vectorizer-Implementation

## Overview
This project involves the implementation of a TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer from scratch and comparing its results with the scikit-learn (Sklearn) implementation. The TF-IDF vectorizer is a crucial component in natural language processing and information retrieval, used to convert a collection of text documents into numerical vectors for analysis.

## Task 1: Build a TF-IDF Vectorizer & Compare with Sklearn
In this task, a custom TF-IDF vectorizer is implemented. The steps involved are as follows:

1. **Fit and Transform Methods**: The custom TF-IDF vectorizer includes the implementation of both the fit and transform methods, allowing it to be applied to a collection of text documents.

2. **Vocabulary Comparison**: The vocabulary generated from the custom implementation is compared to the feature names from the Sklearn TF-IDF vectorizer. 

3. **IDF Values**: The IDF (Inverse Document Frequency) values of the terms in the custom implementation are compared to those in Sklearn's TF-IDF vectorizer.

4. **Normalization**: The output of the custom implementation is a sparse matrix, and it is normalized using L2 normalization.

5. **Results Comparison**: The output of the custom implementation is compared with that of Sklearn's TF-IDF vectorizer.

## Task 2: Implement Max Features Functionality
In this task, the TF-IDF vectorizer is modified to include only the top 50 terms with the highest IDF scores. The steps involved are as follows:

1. **Vocabulary Limitation**: The vocabulary is limited to the top 50 feature names based on their IDF values.

2. **Sorting Vocabulary**: The vocabulary is sorted in descending order of IDF values, and the top 50 terms are included.

3. **Normalization**: The sparse matrix is normalized using L2 normalization.

4. **Result Output**: The output of a single document in the corpus is converted into a dense matrix containing 1 row and 50 columns.

The results are presented in the following code blocks:

```
# Task 1: Custom TF-IDF Vectorizer
# Vocabulary comparison
# IDF values comparison
# Results comparison
```
```
# Task 2: TF-IDF Vectorizer with Max Features
# Vocabulary limitation
# Vocabulary sorting
# Normalization
# Result output
```
