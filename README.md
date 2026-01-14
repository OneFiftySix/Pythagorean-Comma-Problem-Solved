# Pythagorean Comma Problem Solved

**12 step tuning system vs 16 step tuning system**

## Overview
This project analyzes the mathematical and harmonic differences between the traditional **12-step tuning system** and a proposed **symmetric 16-step tuning system**. Using engineered harmonic features and supervised machine learning models, the project evaluates whether the two systems produce measurably distinct mathematical signatures.

## Motivation
The modern 12-step system is asymmetric and relies on irrational frequency approximations, leading to tuning discrepancies known as the *Pythagorean comma*. This project proposes a symmetric system using whole-number frequency ratios and tests its structural consistency using data science and machine learning.

## Data
- Synthetic dataset generated from frequency-ratio rules
- 2,000 chord samples (balanced between both systems)
- 15 engineered harmonic features
- Reproducible data generation
- The dataset is included in the repository under the `data/` directory.

## Methods
- Feature engineering (interval purity, overtone alignment, ratio precision)
- Data scaling and stratified train/test split
- Models evaluated:
  - Random Forest
  - Support Vector Machine
  - Neural Network
  - XGBoost
  - Ensemble model

## Results
- **12-step tuning precision:** 81.4%
- **16-step tuning precision:** 100%
- Models achieved **up to 100% classification accuracy**, indicating strong mathematical separability between tuning systems

## Project Files
- 📓 Jupyter Notebook:  
  `notebooks/pythagorean_comma.ipynb`
- 📊 Presentation Slides (PDF):  
  `reports/capstone_slides.pdf`
- DataSet
- 
## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
