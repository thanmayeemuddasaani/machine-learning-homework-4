# CS5710 Machine Learning — Homework 1 (Fall 2025)

**Student Name:** *M. Thanmayee*  
**Student ID:** *700776997*  
**Course:** CS5710 Machine Learning  
**University:** University of Central Missouri  
## Part C — NLP Coding Tasks

This part of the assignment implements two small NLP pipelines using **spaCy**:

- **Q1:** Tokenization, stopword removal, lemmatization, and POS filtering (keeping only nouns and verbs).
- **Q2:** Named Entity Recognition (NER) and a simple pronoun ambiguity warning.

### Requirements

- Python 3.x
- spaCy

  ## Interpretation 

### Q1 – Tokenization, Stopword Removal, Lemmatization, POS Filtering
After processing the text, only the important words remain.  
Stopwords are removed, and the nouns and verbs are converted to their base forms.  
This simplifies the sentence by keeping only the key actions and objects, making the text easier to analyze.

### Q2 – Named Entity Recognition and Pronoun Ambiguity
The NER model correctly identifies people, organizations, locations, and products in the text.  
The pronouns “He” and “him” can refer to more than one person, so the script shows a warning.  
This makes sense because pronoun ambiguity is a common problem for NLP models.


Install dependencies:

```bash
pip install spacy
python -m spacy download en_core_web_sm


