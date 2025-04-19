# CV-Grader
This project is a Python-based tool designed to evaluate and rank CVs (resumes) based on their relevance to a given job description. It uses OCR (Optical Character Recognition) for text extraction, NLP (Natural Language Processing) for text preprocessing, and a scoring mechanism to rank CVs.

##Usage:
Upload CVs: Upload a ZIP file containing CVs in PDF format.
Extract Text: The tool extracts text from the PDFs using PyMuPDF or Tesseract OCR (if necessary).
Preprocess Text: Text is normalized, tokenized, and lemmatized using SpaCy.
Match Against Job Description: The processed CVs are compared to a predefined job description.
Rank CVs: CVs are scored and ranked based on their relevance to the job description.
Export Results: The top-ranked CVs are displayed and saved to a CSV file.
