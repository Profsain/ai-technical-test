# AI Development Instructor - 30 Minute Technical Exercise

## Goal

Complete a small AI web application.

The project is already mostly finished. You only need to complete the sections marked:

```text
TODO
```

The application flow is:

```text
Browser
  ↓
JavaScript
  ↓
FastAPI
  ↓
FAISS Retriever
  ↓
Relevant Context
  ↓
Ollama LLM
  ↓
JSON Response
  ↓
Browser
```

## Project structure

```text
AI-RAG-Interview/
│
├── app.py
├── knowledge.txt
├── requirements.txt
├── run.bat
│
└── frontend/
    ├── index.html
    ├── style.css
    └── app.js
```

## Before the interview

Make sure Ollama is installed and these models exist:

```bash
ollama pull llama3.2:3b
ollama pull nomic-embed-text
```

Check them with:

```bash
ollama list
```

## Run the project

Install the Python packages:

```bash
pip install -r requirements.txt
```

Then run:

```bash
python app.py
```

Or on Windows, double-click:

```text
run.bat
```

Open:

```text
http://127.0.0.1:8000
```

## Your tasks

Complete the TODO sections in:

- `app.py`
- `frontend/app.js`

Keep your solution simple.
