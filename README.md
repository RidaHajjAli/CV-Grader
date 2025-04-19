# CV-Grader

This project is a Python-based tool designed to evaluate and rank CVs (resumes) based on their relevance to a given job description. It uses OCR (Optical Character Recognition) for text extraction, NLP (Natural Language Processing) for text preprocessing, and a scoring mechanism to rank CVs.

## Features

- Extracts text from PDF files using PyMuPDF and Tesseract OCR.
- Preprocesses text using SpaCy for tokenization, lemmatization, and stopword removal.
- Matches CV content against a job description using token matching and scoring.
- Ranks CVs based on their relevance to the job description.
- Outputs the top-ranked CVs and saves the results to a CSV file.

## Requirements

The following dependencies are required to run the project:

- Python 3.7+
- Tesseract OCR
- PyMuPDF
- SpaCy
- scikit-learn
- pandas
- pdf2image
- pytesseract
- python-Levenshtein

## Installation

1. Install the required system packages:
   ```bash
   apt install tesseract-ocr poppler-utils libtesseract-dev
