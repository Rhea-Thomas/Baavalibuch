# NLP Question-Answer Ranking

## Overview

This repository contains a Python script that performs Natural Language Processing (NLP) tasks related to question-answer ranking. It uses Levenshtein distance and XGBoost for ranking responses to user questions. This README file provides information on how to use the script and explains the code's structure and functionality.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Tasks](#tasks)
- [Results](#results)

## Prerequisites

Before using the code, make sure you have the following dependencies installed:

- Python 3.x
- Required Python packages (install via pip):
  - xgboost
  - numpy
  - Levenshtein
  - concurrent.futures
  - datasets (for loading data)

## Getting Started

1. Clone the repository to your local machine:git clone https://github.com/yourusername/nlp-question-answer-ranking.git
cd nlp-question-answer-ranking
2. Install the dependencies:pip install -r requirements.txt

## Usage 

1. Run the script:python nlp_question_ranking.py
2. Enter a question when prompted.
3. The script  will perform various tasks, including retrieving the closest question based on Levenshtein distance, ranking responses using XGBoost, and ranking responses using a combination of Levenshtein and XGBoost.

## Tasks

The script performs the following tasks:

Task 1: Load the dataset.
Task 2: Retrieve the closest question based on Levenshtein distance.
Task 3: Parallelize the search using Python threads.
Task 4: Rank responses using XGBoost.
Task 5: Rank responses using a combination of Levenshtein and XGBoost.

## Results

The script will display the results for each task, including the closest question, answer, Levenshtein distance, and rankings. Task 5 demonstrates the combined ranking based on both Levenshtein distance and XGBoost.

  
