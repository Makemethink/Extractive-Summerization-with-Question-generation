# Extractive-Summerization-with-Question-generation

Extractive Text Summerization using RBM and MCQ + Fill-me Pattern Question generation with simple ui

This is the project that summerize given huge passage to small size and based upon the summerized passage it generates MCQ and Fill-Me pattern questions with GUI

A "restricted Boltzmann machine" (RBM) is a generative stochastic artificial neural network that can learn a probability distribution over its set of inputs.

RBM used for Summerization
Tkinter used for GUI
PKE used for Keyword Extraction
Wordnet and Conceptnet used for Distractor Generation

Things used / need for the project:

1. Miniconda
2. Jupyter Notebook
3. Internet for generating distractors (Conceptnet API is used)
4. Dependencies including miniconda:

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

UI are given below

0) Processing Window:

![image](https://user-images.githubusercontent.com/45332516/117916883-a470db00-b305-11eb-8244-bfc22c95debb.png)

1) Index Window:

![one](https://user-images.githubusercontent.com/45332516/117916101-1f38f680-b304-11eb-9f67-614cd6f12709.PNG)

2) Summerized text Window:

![four](https://user-images.githubusercontent.com/45332516/117916198-4d1e3b00-b304-11eb-82f5-d5c1098ba50b.PNG)

3) Question Window:

![three](https://user-images.githubusercontent.com/45332516/117916255-6d4dfa00-b304-11eb-9b8a-80e348b4bf02.PNG)

