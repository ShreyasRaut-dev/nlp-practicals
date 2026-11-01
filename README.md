# Natural Language Processing Practicals

Repository containing comprehensive Natural Language Processing (NLP) lab practicals, statistical language modeling, regular expressions, formal automata, tokenization, POS tagging, NER, dependency parsing, text vectorization, text classification, and modern transformer-based summarization developed during academic coursework using Anaconda and Python.

## 📌 Repository Overview

| Practical | Notebook File | Topic | Key Libraries | Description |
| :--- | :--- | :--- | :--- | :--- |
| **Setup** | [`abc.ipynb`](abc.ipynb) | Environment Setup & Downloads | NLTK, spaCy, Pandas | NLTK corpora setup (`punkt_tab`), spaCy `en_core_web_sm` model installation and verification |
| **PR 1** | [`Tokenization1.ipynb`](Tokenization1.ipynb) | Text Preprocessing & Tokenization | NLTK, spaCy | Sentence & word tokenization, stopword filtering, stemming (Porter, Lancaster, Snowball), and lemmatization |
| **PR 2** | [`RegEx2.ipynb`](RegEx2.ipynb) | Regular Expressions & Pattern Matching | Python `re` | Regex pattern matching and validation for emails, phone numbers, and formatted text |
| **Automata** | [`DFA_NFA2.ipynb`](DFA_NFA2.ipynb) | Finite State Automata (DFA/NFA) | Python | State machine simulation implementing deterministic finite automata for binary string validation |
| **PR 2B** | [`PR2B.ipynb`](PR2B.ipynb) | N-Gram Language Modeling & Perplexity | NLTK (Brown Corpus) | Statistical n-gram language models, bigram/trigram probability distributions, and vocabulary perplexity evaluation |
| **PR 3** | [`SpellChecker3.ipynb`](SpellChecker3.ipynb) | Minimum Edit Distance Spell Checker | NumPy | Dynamic programming implementation of Levenshtein Distance matrix for word similarity and error correction |
| **PR 3B** | [`3B.ipynb`](3B.ipynb) | Part-of-Speech (POS) Tagging | NLTK (Treebank) | Statistical POS tagging using Hidden Markov Models (HMM) and Viterbi algorithm |
| **PR 4B** | [`4B.ipynb`](4B.ipynb) | Named Entity Recognition (NER) | spaCy, Scikit-Learn | Entity extraction (PERSON, ORG, GPE) with Precision, Recall, and F1-score evaluation |
| **PR 5B** | [`5B.ipynb`](5B.ipynb) | Dependency Parsing & Syntactic Structure | spaCy (`displaCy`) | Syntactic dependency parsing, grammatical head-child relations, and tree rendering |
| **PR 5** | [`PR5.ipynb`](PR5.ipynb) | Text Representation & Vectorization | Scikit-Learn | Bag-of-Words (CountVectorizer) and Term Frequency-Inverse Document Frequency (TF-IDF) feature extraction |
| **Advanced** | [`TextToNumber.ipynb`](TextToNumber.ipynb) | Text-to-Number Vectorization & DTM | Scikit-Learn, Pandas, Matplotlib | Document-Term Matrix (DTM), Sparse vs. Dense representations, and TF-IDF feature importance bar charts |
| **Classification**| [`Naive_bayes1B.ipynb`](Naive_bayes1B.ipynb) | SMS Spam Text Classification | Scikit-Learn, Pandas | SMS Spam dataset classification with TF-IDF Vectorizer, Multinomial Naive Bayes vs. Logistic Regression comparison |
| **PR 10 / GenAI**| [`1C.ipynb`](1C.ipynb) | Abstractive Text Summarization | Transformers, Datasets, ROUGE | Neural text summarization with `sshleifer/distilbart-cnn-12-6` pipeline, evaluated using ROUGE-1, ROUGE-2, and ROUGE-L |

## 🛠️ Tech Stack & Libraries

- **Python 3.x**
- **Jupyter Notebook / Anaconda**
- **NLTK** (Natural Language Toolkit)
- **spaCy** (`en_core_web_sm`)
- **Hugging Face Transformers** (`transformers`, `datasets`, `rouge-score`, `torch`)
- **Scikit-Learn**
- **Pandas**, **NumPy**, & **Matplotlib**

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/ShreyasRaut-dev/nlp-practicals.git
cd nlp-practicals
```

### 2. Set up a virtual environment (optional but recommended)
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Linux/macOS
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```

---
*Created by [Shreyas Raut](https://github.com/ShreyasRaut-dev)*
