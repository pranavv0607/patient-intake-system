# Patient Intake & Scheduling API

This is a FastAPI project with ngrok tunneling, allowing patient intake form submissions and scheduling.

## Features
- Patient intake API (`/intake/`)
- Scheduling API (`/schedule/`)
- Email notifications (`emailer.py`)
- Runs on FastAPI + Uvicorn + ngrok

## Setup
1. Clone repo
2. Install dependencies: `pip install -r requirements.txt`
3. Update `config.py` with your email credentials
4. Run: `uvicorn main:app --reload`
5. Swagger UI: `http://127.0.0.1:8000/docs`
