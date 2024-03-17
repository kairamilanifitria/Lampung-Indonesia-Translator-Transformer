# Language Translator for Bahasa Lampung-Bahasa Indonesia using Transformer Mechanism

## Introduction

This project aims to develop a language translator for Bahasa Lampung to Bahasa Indonesia using the Transformer mechanism.

## Dataset

The dataset used for this project is lpg-ind.tsv, which is included in this repository.

## Model Development Steps

The model development process involves several stages:

1. Obtaining Data
2. Text Normalization
3. Vectorization and Making Datasets
4. Positional Encoding Matrix
5. Positional Encoding Layer
6. Transformer Building Blocks
7. Transformer Encoder and Decoder
8. Building a Transformer
9. Preparing the Transformer Model for Training
10. Training the Transformer
11. Inference from the Transformer Model
12. BLEU Testing

## Performance Metrics
The model achieved an **accuracy** of **0.8085** 
The model achieved **BLEU score** of **0.70** based on a total of 20 testing data results.

## Suggestions for Improvement
To enhance the performance of the model, the following suggestions are recommended:

1. Utilize the NLTK library, which provides better tokenizers compared to simple tokenizers for text input.
2. Use the pre-trained embeddings like GloVe to improve the quality of embeddings.
3. Fine-tune parameters such as the number of epochs, learning rate schedule, and loss function, as they can significantly impact the performance of the transformer.
