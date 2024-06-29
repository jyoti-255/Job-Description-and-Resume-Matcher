# Job Description and Resume Matcher 📄🔍

## Overview

This Flask application allows you to match job descriptions with multiple resumes to find the best matches based on cosine similarity scores.

## Features

- **Upload Resumes:** Upload multiple resumes in PDF, DOCX, or TXT formats.
- **Enter Job Description:** Input the job description to compare against the uploaded resumes.
- **Cosine Similarity Matching:** Utilizes TF-IDF vectorization and cosine similarity to rank resumes based on similarity to the job description.
- **Top Matches:** Displays the top matching resumes and their similarity scores.

## Setup

### Requirements

- Python 3.x
- Flask
- PyPDF2
- docx2txt
- scikit-learn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your/repository.git
   cd job-description-resume-matcher
   
pip install Flask PyPDF2 docx2txt scikit-learn

cd job-description-resume-matcher

python app.py
## Usage

- **Home Page:** Upload resumes and enter a job description.
- **Matching Page:** View the top matching resumes and their similarity scores.

## Files and Structure

- **app.py:** Flask application with routing and matching logic.
- **matchresume.html:** HTML template for user interface.
- **uploads/:** Folder to store uploaded resumes temporarily.

