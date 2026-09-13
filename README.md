# AI Resume Screening System — Week 2: Data Cleaning and Transformation

Week 2 deliverable for the Virtual Data Science Apprenticeship (Python Specialist Intern track). This week documents the data-wrangling strategy that turns raw, noisy resume and job-description text into a clean, structured, analysis-ready dataset.

## Contents

- `Week2_Data_Cleaning_and_Transformation.docx` — full cleaning & transformation plan

## What's in the Report

- **Data Quality Issues Identified** — duplicates, missing fields, inconsistent casing/whitespace, PDF boilerplate noise, outlier/malformed rows, non-standardized skill naming
- **Cleaning Strategy**
  - Deduplication (exact + near-duplicate via TF-IDF cosine similarity)
  - Missing-value handling with logged imputation
  - Outlier detection (token-length thresholds, IQR analysis)
  - Text normalization (lowercasing, lemmatization, boilerplate removal)
  - Skill normalization (synonym dictionary, fuzzy matching)
- **Transformation Pipeline** — Raw Text → Deduplicate → Handle Missing → Normalize Text → Extract & Normalize Skills → Clean Dataset
- **Feature Engineering** — TF-IDF vectors, scaled numeric features, encoded labels, binary skills-presence matrix
- **Tools** — pandas, numpy, re, nltk/spaCy, scikit-learn, textdistance/rapidfuzz

## Status

Cleaning and transformation plan complete. Proceeds into Week 3 (exploratory data analysis).
