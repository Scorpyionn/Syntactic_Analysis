# Natural Language Processing – Practical Experiments

## Overview

This repository contains practical implementations of Natural Language Processing (NLP) techniques using Python and popular NLP libraries.

The experiments demonstrate text processing, feature extraction, linguistic analysis, named entity recognition and syntactic parsing through practical examples and visualizations.

## Technologies Used

- Python 3
- Google Colab
- NLTK
- Scikit-learn
- spaCy
- Berkeley Neural Parser (benepar)
- Pandas
- Matplotlib
- Seaborn

## Experiments Included

| Experiment | Title | Tools |
|---|---|---|
| 04 | Bag-of-Words and N-Gram Models | Scikit-learn |
| 05 | Morphological Analysis and POS Tagging | NLTK |
| 06 | Named Entity Recognition (NER) | spaCy |
| 07 | Syntactic Analysis | spaCy, benepar |

## Experiment Details

### Experiment 4: Bag-of-Words and N-Gram Models
- Bag-of-Words representation
- Unigram generation
- Bigram generation
- Trigram generation
- Word frequency analysis
- Frequency visualization

### Experiment 5: Morphological Analysis and POS Tagging
- Tokenization
- Stemming
- Lemmatization
- POS tagging
- Noun phrase chunking
- POS frequency distribution

### Experiment 6: Named Entity Recognition
- Named entity extraction
- Entity classification
- Entity visualization using displaCy
- Entity frequency analysis
- Bar chart and heatmap visualization

### Experiment 7: Syntactic Analysis
- Constituency parsing
- Dependency parsing
- Parse tree generation
- Grammatical relationship extraction
- Dependency visualization
- Dependency relation frequency analysis

## Repository Structure

```text
NLP_Practical_Experiments/
│
├── Experiment_4_BOW_NGRAM.ipynb
├── Experiment_5_Morphological_Analysis.ipynb
├── Experiment_6_Named_Entity_Recognition.ipynb
├── Experiment_7_Syntactic_Analysis.ipynb
│
├── README.md
├── README_Experiment_7.md
├── requirements.txt
└── .gitignore
```

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/NLP_Practical_Experiments.git
```

Navigate to the project:

```bash
cd NLP_Practical_Experiments
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Download the required spaCy model:

```bash
python -m spacy download en_core_web_sm
```

Download the benepar model:

```python
import benepar
benepar.download("benepar_en3")
```

## How to Run

1. Open the required `.ipynb` notebook.
2. Upload it to Google Colab or open it using Jupyter Notebook.
3. Install the required libraries.
4. Execute the code cells sequentially.
5. Observe the generated tables, outputs and visualizations.

## Applications of NLP

- Text Classification
- Sentiment Analysis
- Information Extraction
- Natural Language Understanding
- Machine Translation
- Question Answering
- Text Mining

## Purpose

This repository is created for academic learning and practical implementation of Natural Language Processing concepts using Python.

---

**Technologies:** Python | NLTK | Scikit-learn | spaCy | benepar | Pandas | Google Colab
