# AI Resume Ranker

This project is an AI-powered tool designed to evaluate how well a resume matches a given job description. It leverages spaCy for natural language processing, Flask for API integration, and React for the user interface. The tool helps recruiters and job seekers assess alignment between resumes and role requirements.

## Features

- Upload resume and job description files (TXT or PDF)
- NLP-based matching using spaCy and semantic similarity techniques
- Real-time match scoring and comparison
- Lightweight Flask API for backend processing
- React-based frontend for user interaction
- Optional AWS Lambda integration for cloud-based processing

## Use Cases

- Recruiters filtering large volumes of resumes
- Job seekers tailoring resumes for specific roles
- Career platforms providing real-time feedback

## Project Structure

- `backend/app.py` – Flask API that handles resume and JD parsing, similarity scoring
- `frontend/src/App.js` – React component for file upload and result display
- `nlp/matcher.py` – spaCy logic for text extraction and scoring
- `lambda/resume_handler.py` – (Optional) AWS Lambda function for serverless inference
- `screenshots/screenshot.png` – Sample UI for resume upload and score output

## Tech Stack

- Python (Flask, spaCy)
- React (JavaScript)
- AWS Lambda (Optional)
- HTML, CSS
- Docker-ready structure

## Installation

1. Clone the repository

```bash
git clone https://github.com/praveenkt2001/resume_ranker_ai.git
cd resume_ranker_ai
Set up backend

bash
Copy
Edit
cd backend
pip install -r requirements.txt
python app.py
Run frontend (in a separate terminal)

bash
Copy
Edit
cd frontend
npm install
npm start
Access the application at http://localhost:3000

