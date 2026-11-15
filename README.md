# NLP Assignment 2 — Word Embeddings Lab

Lab for MSAI6320 (Natural Language Processing), Birzeit University, based on Jurafsky & Martin, Chapter 5.

The notebook `Embedding.ipynb` covers:

1. Loading and tokenizing a subset of the Quora Question Pairs dataset
2. Training Word2Vec (Skip-gram and CBOW) from scratch with gensim
3. Comparing context window sizes and model types, with written analysis
4. Exploring and visualizing the learned embeddings

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook Embedding.ipynb
```

## Data

The dataset file `quora.txt` (~33 MB) is not tracked in this repo. Place it in the project root before running the notebook (see the notebook's Part 1 for the source).
