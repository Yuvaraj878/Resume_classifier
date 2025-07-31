# Resume Classification with TF-IDF & Logistic Regression

This repository contains an end-to-end pipeline for classifying resumes into job categories using natural language processing (NLP) and machine learning. We leverage **spaCy** for text preprocessing and **scikit-learn** for TF-IDF vectorization and model training.

---

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Dataset](#dataset)

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
```

## Installation

Clone this repository:

```bash
git clone https://github.com/your-username/resume-classifier.git
cd resume-classifier

```

## Dataset
Place your CSV file named UpdatedResumeDataSet.csv in the project root. Ensure it contains at least two columns:

  Resume: raw text of the candidate's resume

  Category: target job category label

Resume,Category
"Experienced software engineer with expertise in Python, Java, and machine learning projects.","Software Engineer"
"Detail-oriented accountant proficient in QuickBooks, financial reporting, and tax planning.","Accountant"
"Marketing specialist skilled in SEO, content creation, and social media management.","Marketing Specialist"
"Registered nurse with strong patient care, clinical assessment, and medication administration experience.","Nurse"

