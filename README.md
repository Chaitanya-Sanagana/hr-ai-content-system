---
title: HR AI Content System
emoji: 📂
colorFrom: blue
colorTo: indigo
sdk: gradio
app_file: app.py
pinned: false
---

# 🤖 HR AI Content System

An AI-ready content engineering demo for transforming HR policy text into structured, retrievable, governed knowledge assets.

This project shows how enterprise content can be prepared for AI-powered employee support using ingestion, chunking, metadata, embeddings, retrieval, RBAC-style filtering, PII redaction, and evaluation.

## What it demonstrates

- AI-ready content pipeline design
- HR knowledge-base preparation
- Semantic chunking
- Metadata and taxonomy tagging
- Sentence Transformer embeddings
- Vector-style similarity retrieval
- Role-based answer filtering
- PII redaction patterns
- Golden-set evaluation workflow
- Gradio demo interface

## Why it matters

Many enterprise AI projects fail because the underlying content is messy, unstructured, or weakly governed. This project demonstrates the content-preparation layer needed before HR knowledge can be safely reused in AI search, assistants, or employee self-service workflows.

## Features

- Load sample HR policy content
- Split content into retrievable chunks
- Attach document metadata
- Generate embeddings
- Retrieve top matching policy chunks
- Apply employee/HR role filtering
- Redact sensitive text for employee-facing answers
- Run a simple evaluation set for expected-answer coverage
- Safely reject irrelevant queries when confidence is low

## Tech stack

- Python
- Gradio
- Sentence Transformers
- NumPy
- Scikit-learn

## Project structure

```text
hr-ai-content-system/
├── app.py
├── requirements.txt
├── .env.example
├── .gitignore
├── DEPLOYMENT_CHECKLIST.md
├── README.md
├── pipeline/
│   ├── __init__.py
│   ├── ingestion.py
│   ├── chunking.py
│   ├── metadata.py
│   ├── embeddings.py
│   ├── retrieval.py
│   ├── governance.py
│   └── evaluation.py
└── data/
    └── sample_hr_docs.txt
```

## Example questions

- How many PTO days do employees get?
- Can PTO be carried over?
- How long is parental leave?
- How many sick leave days are given?
- How many days can employees work remotely?
- What sensitive information should not be shared?

## Run locally

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

On Windows PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python app.py
```

## Environment variables

The default demo does not require API keys. Embeddings run locally through Sentence Transformers.

Use `.env.example` as a safe template only. Do not commit a real `.env` file.

## Deployment notes

This project is compatible with Hugging Face Spaces using the Gradio SDK metadata at the top of this README.

Suggested Space name:

```text
hr-ai-content-system
```

## Limitations

- Uses sample HR content, not a real enterprise HRIS or document repository.
- Retrieval is local and lightweight.
- RBAC and PII filtering are demo patterns, not enterprise identity controls.
- This project is for AI engineering portfolio demonstration, not HR/legal advice.

## Roadmap

- Add file upload for custom HR documents
- Add richer metadata taxonomy
- Add department/region filters
- Add stronger PII detection
- Add answer citation formatting
- Add dashboard-style retrieval evaluation metrics

## Author

**Chaitanya S.**  
Applied AI Engineer | Generative AI · RAG · Agentic AI · AI Platform Engineering

- GitHub: `github.com/ChaitanyaAI-Dev/hr-ai-content-system`
- LinkedIn: `linkedin.com/in/chaitanyaai-dev`
- Hugging Face: `huggingface.co/ChaitanyaAI-Dev`
- Portfolio: `chaitanyaai-dev-portfolio.vercel.app`

## Disclaimer

This is a prototype/demo project for AI engineering portfolio purposes. It is not HR, legal, regulatory, or compliance advice.
