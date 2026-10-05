# Exploratory Data Analysis

A Python-based social media analytics project focused on understanding gender-specific language patterns, tweet behavior, and classification performance. The project uses a cleaned dataset of social media profiles and text content to explore word usage, compare male and female communication trends, and evaluate machine learning models for gender prediction.

## Project overview

This repository contains:
- A Jupyter notebook for data cleaning, exploratory analysis, and model evaluation
- A synthetic dataset for analysis and experimentation
- Summary results and visual insights from the project

## Objectives

- Analyze the most common words used by male and female users
- Compare tweet activity and engagement patterns by gender
- Study key dataset attributes such as tweet count, retweet count, and favorites
- Evaluate multiple classification algorithms for gender prediction
- Identify the model with the best performance for this dataset

## Dataset

The project uses a social media-style dataset with attributes such as:
- _unit_id
- gender
- description
- fav_number
- retweet_count
- text
- tweet_count

A sample dataset file is included in the repository as:
- Information.csv

## Methodology

The workflow includes:
1. Loading and inspecting the dataset
2. Selecting relevant columns for analysis
3. Cleaning and filtering gender labels
4. Performing exploratory text analysis
5. Visualizing most frequent words by gender
6. Applying machine learning classification models
7. Comparing model accuracy and selecting the best-performing algorithm

## Key findings

From the project summary:
- The most common word used by males was "the"
- The most common word used by females was "and"
- The highest tweet count recorded for a male was 110964
- The highest tweet count recorded for a female was 31462
- Decision Tree classification produced the highest accuracy among the models tested

## Technologies used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Natural language processing (text preprocessing and word frequency analysis)

## Repository structure

```text
Exploratory-data-analysis/
├── ML-MAJOR-JUNE-ML062B11.ipynb
├── Information.csv
├── README.md
└── ML-MAJOR-JUNE-ML062B11.pdf
```

## How to run

1. Open the notebook in Jupyter:
   ```bash
   jupyter notebook ML-MAJOR-JUNE-ML062B11.ipynb
   ```
2. Ensure required Python libraries are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Run the cells in sequence to reproduce the analysis.

## Notes

This project demonstrates a practical exploratory data analysis and machine learning workflow for social media text data, including gender-based pattern analysis and supervised classification.
