# AI Resume Screening System

> Fork notice: this repository is forked from `tasnem-tech/AI-Resume-Screening-System`. Review and document Sachin's specific contributions before presenting it as authored work.

## Overview

A Streamlit machine-learning application that compares resume text with a job description using NLP and produces a similarity-based match score.

## Features

- Resume text analysis
- Job description matching
- Match percentage calculation
- NLP-based text processing
- Machine-learning scoring
- Interactive Streamlit dashboard

## Tech Stack

- Python
- Streamlit
- scikit-learn
- NLP text processing
- Pandas

## Architecture

```text
Resume + job description
          -> text preprocessing
          -> feature extraction
          -> similarity calculation
          -> match score
          -> Streamlit dashboard
```

## Screenshots

Add a real repository-local screenshot of the Streamlit dashboard. The current README contains a screenshot placeholder.

## Installation

```bash
git clone https://github.com/Sachin1885/AI-Resume-Screening-System.git
cd AI-Resume-Screening-System
pip install -r requirements.txt
streamlit run app.py
```

## Environment Variables

No environment variables are documented in the current repository README.

## Usage

Use the Streamlit interface with a resume and job description. Keep resume data private and avoid uploading sensitive personal information to untrusted deployments.

## API

This is documented as a Streamlit application; no HTTP API is documented in the current repository.

## Live Demo

[ai-resume-screening-system.streamlit.app](https://ai-resume-screening-system.streamlit.app/)

## Future Improvements

The current README proposes PDF/DOCX parsing, transformer models, ATS scoring, skill-gap analysis, multilingual support, recruiter dashboards, and candidate ranking. Label these as roadmap items, not current functionality.

## Author

[Sachin Kumar](https://github.com/Sachin1885)
