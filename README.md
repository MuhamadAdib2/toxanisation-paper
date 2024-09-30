NLP Preprocessing and Tokenization Project
Overview
This project explores the impact of various NLP preprocessing techniques, including tokenization (SentencePiece, BPE), stemming, and lemmatization, on text classification using the IMDB dataset.

Key Components
Tokenization: SentencePiece, Byte-Pair Encoding (BPE).
Stemming: Porter, Lancaster, and Snowball Stemmers.
Sentiment Analysis: Evaluates the impact of different preprocessing methods on classification accuracy.
Files
SentencePieceTokenization.ipynb – Implements SentencePiece tokenization for multilingual text.
Stemmer.ipynb – Compares stemming techniques for sentiment classification.
NLP Paper (Tokenization).pdf – Research paper detailing the experiments and results.
Setup
Install required libraries:
Copy code
pip install sentencepiece nltk sklearn
Run the Jupyter notebooks:
Copy code
jupyter notebook SentencePieceTokenization.ipynb
jupyter notebook Stemmer.ipynb
Results
SentencePiece: Effective for multilingual tokenization.
IMDB Sentiment Analysis: Unprocessed text achieved the highest accuracy (85.2%).
