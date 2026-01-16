# AIG 230 – Lab 2  
## Text, Corpus, and Tokenization in Practice

This lab focuses on the **foundations of Natural Language Processing (NLP)**, with an emphasis on how text is represented, processed, and prepared for analysis in real-world workflows.

Rather than treating NLP as a collection of abstract techniques, this lab mirrors how text analysis is approached in **industry, research, and policy contexts**.

---

## 🎯 Learning Objectives

By completing this lab, you will be able to:

- Distinguish between **raw text**, **documents**, and a **corpus**
- Load and explore a **real-world text corpus**
- Understand why corpus exploration comes *before* preprocessing
- Perform **word and sentence tokenization**
- Compare **NLTK and spaCy** for the same NLP tasks
- Apply **normalization techniques**, including:
  - lowercasing  
  - stop word removal  
  - stemming  
  - lemmatization  
- Understand **Byte Pair Encoding (BPE)** and why it is used in modern NLP systems
- Reason about **preprocessing trade-offs**, not just apply them

---


## 📘 Notebook Overview

### 1️⃣ `nlp_text_processing.ipynb`

This is the **main lab notebook**.

You will work with the full **State of the Union corpus**, a collection of U.S. presidential addresses spanning over two centuries.

Key topics covered:

- What makes a collection of texts a **corpus**
- Exploratory analysis of raw text
- Word and sentence tokenization
- Side-by-side comparison of **NLTK vs spaCy**
- Normalization choices and their implications
- Stop words, stemming, and lemmatization
- Vocabulary construction and frequency analysis
- Industry-style reflection questions

This notebook emphasizes **explicit, transparent NLP pipelines**, not hidden helper functions.

---

### 2️⃣ `bpe_state_of_the_union_demo.ipynb`

This notebook is a **conceptual and practical introduction to Byte Pair Encoding (BPE)**.

You will:

- Train a small BPE tokenizer on State of the Union text
- Inspect the learned subword vocabulary
- Compare word-level tokens with subword tokens
- Understand how modern language models tokenize text

This notebook exists to build **correct mental models** about modern NLP and how it differs from classical word-based approaches.

---

## 🛠 Setup Instructions

You may run these notebooks locally or in a cloud environment.

### Required Python packages

```bash
pip install nltk spacy tokenizers
```

### Additional setup

If needed, install the spaCy English model:

```bash
python -m spacy download en_core_web_sm
```

---

## 🧪 What You Are Expected to Do

You are expected to:

- Run all cells in both notebooks
- Complete the exercises and reflection questions in the main lab notebook
- Modify code where prompted
- Demonstrate understanding of **why** preprocessing decisions are made

This lab is not about memorizing functions.  
It is about **reasoning about text as data**.

---

## 🧠 Key Takeaway

There is no single “correct” NLP pipeline.

Every preprocessing choice:
- encodes assumptions
- affects downstream analysis
- depends on the task and domain

Understanding these trade-offs is a core skill in applied NLP.

---

## 📌 Submission Instructions

Follow the instructions provided in class for submitting Lab 2.

Typically, this includes:
- Pushing your completed notebook(s) to your GitHub lab repository
- Submitting the repository link on Blackboard

---
### Deliverables
- Completed notebook
- All code pushed to your own GitHub repository


