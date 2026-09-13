# AI Resume Screening System — Week 4: ML Model Selection and Evaluation Plan

Week 4 deliverable for the Virtual Data Science Apprenticeship (Python Specialist Intern track). This week defines how the AI Resume Screening System selects, trains, and evaluates its machine learning models — the final step in the project's design.

## Contents

- `Week4_ML_Model_Selection_and_Evaluation.docx` — full model selection and evaluation plan

## What's in the Report

- **Problem Framing** — Task A: resume classification into job categories (supervised); Task B: resume-to-job similarity scoring (unsupervised)
- **Candidate Classification Models** — Logistic Regression (baseline), Multinomial Naive Bayes, Random Forest, Linear-kernel SVM, each with a stated rationale
- **Similarity Scoring Approach** — TF-IDF cosine similarity baseline, skill-overlap enhancement, embedding-based stretch goal
- **Evaluation Metrics** — accuracy, precision, recall, F1, macro-averaged F1 (primary metric), confusion matrix, ROC-AUC
- **Workflow** — Train/Val/Test Split → Train Candidate Models → Evaluate & Compare → Select Best Model → Error Analysis
- **Validation Strategy** — stratified 70/15/15 split, 5-fold stratified cross-validation, test set touched only once
- **Practical Applicability** — explainable, auditable outputs suited to a real hiring workflow

## Status

Model selection and evaluation plan complete. This closes out the four-week design phase for the AI Resume Screening System.
