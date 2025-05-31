# Text Summarization Web App

A web application for summarizing long-form text using machine learning. Built with Python, Django, and PyTorch.

## Features

* Extractive and abstractive summarization
* ML backend with PyTorch and NLP models
* Django-based web interface
* API endpoints for integration

## Tech Stack

* **Backend**: Python, Django
* **ML/NLP**: PyTorch, Transformers, spaCy, NLTK
* **Frontend**: HTML, CSS (optional Bootstrap)

## Setup

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/text-summarization-django.git
   cd text-summarization-django
   ```

2. Create virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the server:

   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

Visit `http://127.0.0.1:8000` to use the app.

## Project Structure

```
text-summarization-django/
├── summarizer/        # Django app with ML logic
├── templates/         # HTML templates
├── static/            # CSS/JS (if any)
├── manage.py
└── requirements.txt
```

## Future Improvements

* User login and history
* File upload (PDF, DOCX)
* Deployment with Docker or cloud
