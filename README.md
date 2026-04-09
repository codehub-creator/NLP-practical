# NLP Tokenization, Stemming, and Lemmatization using NLTK

This project demonstrates fundamental Natural Language Processing (NLP) techniques using the NLTK library in Python. It includes multiple tokenization methods, stemming algorithms, and lemmatization applied to a sample sentence.

---

## Overview

The goal of this project is to understand and implement essential NLP preprocessing steps such as tokenization, stemming, and lemmatization. These techniques are widely used in text analysis, machine learning, and information retrieval systems.

---

## Features

### Tokenization Techniques
- Whitespace Tokenization
- Punctuation-based Tokenization
- Treebank Tokenization
- Tweet Tokenization
- Multi-Word Expression (MWE) Tokenization

### Stemming Techniques
- Porter Stemmer
- Snowball Stemmer

### Lemmatization
- WordNet Lemmatizer

---

## Theory

Natural Language Processing (NLP) involves processing and analyzing textual data. Tokenization is the process of splitting text into smaller units such as words or phrases. Stemming reduces words to their base form by removing suffixes, often producing non-dictionary words. Lemmatization improves upon stemming by converting words into their meaningful base form using linguistic rules and vocabulary. These preprocessing steps help improve the efficiency and accuracy of NLP applications.

---

## Technologies Used

- Python
- NLTK (Natural Language Toolkit)

---
## Project Structure
├── main.py
├── README.md


---

## Setup and Installation

### Prerequisites
- Python 3.x installed

### Steps

1. Clone the repository:
   git clone https://github.com/codehub-creator/NLP-practical.git

cd NLP-practical


2. Create a virtual environment (optional but recommended):
   python -m venv venv

   
3. Activate the virtual environment:

- Windows:
  venv\Scripts\activate
- macOS/Linux:
  source venv/bin/activate


4. Install dependencies:
   pip install nltk
   
5. Download required NLTK datasets:
   python
   Then run:
   import nltk
  nltk.download('punkt')
  nltk.download('wordnet')
  nltk.download('omw-1.4')


---

## Usage

Run the program:
python main.py

---

## Sample Input
NLTK is a powerful library for Natural Language Processing!


---

## Output

The program performs:
- Tokenization using different techniques
- Stemming using Porter and Snowball stemmers
- Lemmatization using WordNet

---

## Future Enhancements

- Extend to larger datasets
- Add visualization of results
- Integrate with machine learning models

---


## License

This project is for educational purposes.


