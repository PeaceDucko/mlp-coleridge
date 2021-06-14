# Let US show you the data
This repository houses notebooks belonging to the "Coleridge Initiative - Show US the data" competition, hosted by Kaggle. The notebooks have been set up by three students of team 2 of the Radboud University Masters course "Machine Learning in Practice".

# Dataset
The dataset consists of 14.000 training publications with 130 unique labels. The  hidden test set has roughly ~8.000 publications, many times the size of the public test set.

# Goal
The goal of this competition is to predict the occurance of data set labels within the text of scientific publication using natural language processing techniques.

# Methods
We attempted a named entity recognition (NER) approach using the spaCy library. Our best model originated from a SciBERT pretrained transformer and resulted in a public score of 0.028.

# Specifications
The notebooks present in this repository were directly downloaded from Kaggle. The notebooks were written in Python and ran on a Kaggle GPU accelerator. Additionally, libraries like spaCy, PyTorch, NLTK and Huggingface Transformers were used in combination with our own generated data sets.

# Notebooks referenced
Prashans Dixit (2021, April). 📝Coleridge Initiative-EDA📚 & Baseline Model🎯. https://www.kaggle.com/prashansdixit/coleridge-initiative-eda-baseline-model
