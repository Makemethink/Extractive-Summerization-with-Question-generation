# Extractive-Summerization-with-Question-generation

Extractive Text Summerization using RBM and MCQ + Fill-me Pattern Question generation

This is the project that summerize given huge passage to small size and based upon the summerized passage it generates MCQ and Fill-Me pattern questions

A "restricted Boltzmann machine" (RBM) is a generative stochastic artificial neural network that can learn a probability distribution over its set of inputs.

Things used for the project:

1. Miniconda
2. Jupyter Notebook
3. Internet for generating distractors (Conceptnet API is used)

Dependencies including miniconda:

01. Numpy
02. Nltk [import nltk ; nltk.download('stopwords') ; nltk.download('popular')]
03. Rake_nltk
04. Image
05. Theano
06. Pandas
07. Pke (!pip install git+https://github.com/boudinfl/pke.git)
08. Skfuzzy
09. Scikit-learn
10. Spacy [with en language] (!python -m spacy download en ; !pip install spacy==2.1.3 --upgrade --force-reinstall)
11. Flashtext
12. Wordnet
14. Wn