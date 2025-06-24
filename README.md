# PowerPoint Template Generator

This project provides a simple example of generating a PowerPoint presentation from a text prompt. A FastAPI backend creates the presentation and a minimal frontend allows you to submit a prompt.

## Running the application

1. Install Python dependencies:
   ```bash
   pip install -r backend/requirements.txt
   ```
2. Start the development server:
   ```bash
   uvicorn backend.app.main:app --reload --port 8000
   ```
3. Open `http://localhost:8000` in your browser and generate a slide.

The generated PowerPoint file will be downloaded automatically after submission.
