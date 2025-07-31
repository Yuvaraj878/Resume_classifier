# Resume Classification with TF-IDF & Logistic Regression

This repository contains an end-to-end pipeline for classifying resumes into job categories using natural language processing (NLP) and machine learning. We leverage **spaCy** for text preprocessing and **scikit-learn** for TF-IDF vectorization and model training.

---

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Dataset](#dataset)
- [Directory Structure](#directory-structure)
- [Usage](#usage)
  - [1. Preprocessing](#1-preprocessing)
  - [2. Vectorization](#2-vectorization)
  - [3. Model Training](#3-model-training)
  - [4. Evaluation](#4-evaluation)
- [Example Predictions](#example-predictions)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- **Tokenization, lemmatization, and stopword removal** with spaCy  
- **TF-IDF** vector representation of resume text  
- **Logistic Regression** classifier for job category prediction  
- **Train/test split** with stratification for balanced evaluation  
- Accuracy reporting and sample prediction outputs  

---

## Prerequisites

Ensure you have Python 3.7+ installed.

Required packages:

- pandas  
- spacy  
- scikit-learn  

Additionally, download the spaCy English model:

```bash
python -m spacy download en_core_web_sm
