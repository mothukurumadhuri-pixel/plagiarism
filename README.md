# AI Plagiarism Checker

## Overview

This project is a simple AI-powered plagiarism detection system developed using Python and Scikit-learn. It compares multiple text documents and calculates their similarity using TF-IDF Vectorization and Cosine Similarity.

## Features

* Detects similarity between text documents
* Uses TF-IDF Vectorization
* Uses Cosine Similarity for comparison
* Supports multiple text files
* Generates plagiarism similarity scores
* Easy to understand and implement

## Technologies Used

* Python
* Scikit-learn
* TF-IDF Vectorizer
* Cosine Similarity

## Project Structure

```
task3plagiarismchecker
│
├── student1.txt
├── student2.txt
├── student3.txt
├── plagiarism_checker.ipynb
├── requirements.txt
└── README.md
```

## How It Works

1. Reads all text files from the specified directory.
2. Converts text documents into TF-IDF vectors.
3. Calculates cosine similarity between every pair of documents.
4. Displays similarity scores.
5. Higher similarity indicates possible plagiarism.

## Sample Output

```
PLAGIARISM REPORT

student1.txt ↔ student2.txt
Similarity: 100.00%

student1.txt ↔ student3.txt
Similarity: 16.99%

student2.txt ↔ student3.txt
Similarity: 16.99%
```

## Installation

Install the required package:

```bash
pip install -r requirements.txt
```

## Run the Project

Open Jupyter Notebook and run:

```bash
jupyter notebook
```

Then execute all cells in `plagiarism_checker.ipynb`.


## Internship Task

Task 3 – Combat Online Plagiarism with Artificial Intelligence.
