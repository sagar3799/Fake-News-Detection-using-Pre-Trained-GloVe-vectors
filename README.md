# Fake-News-Detection-using-Pre-Trained-GloVe-vectors

## Introduction
Fake news is a major concern in our society right now. It has gone hand-in-hand with the rise of the data-driven era – not a coincidence when you consider the sheer volume of data we are generating every second! 
Natural Language Processing (NLP ) techniques are being used to generate fake articles – a concept called “Neural Fake News”.
Advanced pre-trained NLP models like BERT, GPT-2, XLNet, etc. are easily available for anyone to download and play around with. This aggravates the risk of them being exploited for spreading propaganda and chaos in society.
This is an attempt to detect such hoaxes using simple NLP techniques.

## Overview
This Neural model was trained on a GPU provided by kaggle.
It uses pre-trained GloVe embeddings which can be downloaded from [here](https://nlp.stanford.edu/projects/glove/) or [here.](https://www.kaggle.com/jdpaletto/glove-global-vectors-for-word-representation)

## Dataset
This dataset(~41MB zip) can be downloaded from [here.](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

## Dependencies
* pip install tensorflow
* pip install keras
* pip install nltk

## Acknowlegdements
* [GloVe: Global Vectors for Word Representation](https://nlp.stanford.edu/projects/glove/)
