# LING406: Intro to Computational Linguistics (Spring 2025)

This repository contains coursework for LING406 at UIUC. Below is a summary of each assignment and its core objective.

---

## Assignment 1: Temporal Named Entity Recognition
**Task:** Build a system using regular expressions to detect fixed date expressions and U.S. holidays in unstructured text.  

**Output:** Extracted date expressions written to `output.txt`.

---

## Assignment 2: N-Gram Language Modeling for Language Identification
**Task:** Use character and word-level N-gram models to classify sentences into English, French, or Italian.  
**Experiments:**  
- Letter bigram model with add-one smoothing  
- Word bigram model with add-one smoothing  
- Word bigram model with Good-Turing smoothing

**Output:** Language prediction per line of the test file.

---

## Assignment 3: POS Tagging (PolEval Dataset)
**Task:** Implement supervised machine learning models to predict part-of-speech tags for Polish text.  
**Components:**  
- Baseline system with bag-of-words context features  
- Improved system with enhanced feature engineering  
- Feature ablation analysis

**Output:** Performance metrics and error analysis.

---

## Term Project: Sentiment Classifier Using ML/DL
**Task:** Build a sentiment classifier for movie reviews (positive/negative).  
**Workflow:**  
- Start with a baseline model  
- Compare multiple algorithms  
- Try various feature engineering approaches  
- Train and evaluate an improved final system

**Dataset:** Cornell movie review polarity dataset  
**Extra credit:** Optional advanced tasks like syntax-aware features or domain transfer to Yelp data.

---

Each assignment folder contains the code, output files, and report for the corresponding task. See individual subfolders for instructions on running the code.
