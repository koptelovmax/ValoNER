# ValoNER : a tool for criteria identification and ranking using named entities on valorization of agricultural residues
The code to support our submission "Automating criteria identification and ranking in qualitative data analysis on valorization of agricultural residues" to the Artificial intelligence in agriculture journal

## Structure of the repository

### ValoNER tool:

- **Home.py** -- the homepage of the web application providing an interface for named-entity recognition and their ranking

## To run the web application on a local machine:

### Installation

There are a number of Python packages that need to be installed to run the application:

1. Install streamit library for running web application
```sh
pip install streamlit
```
2. Install transformers library for natural language processing (NLP)
```sh
pip install transformers
```
3. Install torch library for deep learning and tensor computations
```sh
pip install torch
```
4. Install nltk and spaCy libraries for text processing and NLP

```sh
pip install nltk spacy
```
5. Install sentencepiece library for text tokenization

```sh
pip install sentencepiece
```
6. Install Gliner library for named-entity recognition

```sh
pip install gliner 
```
7. Install sentence-transformers library for text to embedding vector encoding

```sh
pip install sentence-transformers
```
8. Install numpy library for numerical computations

```sh
pip install numpy
```
For exact versions of packages please look at the *requirements.txt* file.

### To run the application

```sh
streamlit run Home.py
```
