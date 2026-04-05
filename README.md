---
title: HR AI Content System
emoji: 📂
colorFrom: blue
colorTo: indigo
sdk: streamlit
app_file: app.py
pinned: false
---

# 🤖 HR AI Content System

An AI-ready content optimization system that transforms unstructured HR content into structured, governed, and retrievable knowledge assets.

This project demonstrates how enterprise HR content can be prepared for AI-powered employee experiences using semantic processing, metadata design, governance controls, and retrieval workflows.

---

## Problem

HR knowledge is often scattered across policy documents, FAQs, and internal content that may be difficult to search, govern, or reuse effectively in AI systems.

Common issues include:

- Unstructured or inconsistent content
- Weak discoverability
- Poor metadata and taxonomy
- Lack of governance controls
- Limited readiness for AI retrieval systems

---

## Solution

HR AI Content System simulates a full AI-ready content pipeline for HR knowledge.

It includes:

- Content ingestion
- Semantic chunking
- Metadata tagging
- Embeddings and retrieval
- Governance controls
- Evaluation workflows

The goal is to convert raw HR content into structured knowledge that is easier to retrieve, govern, and use safely in AI-driven employee support experiences.

---

## Key Features

- AI-ready HR content pipeline
- Semantic chunking and structured formatting
- Metadata tagging and traceability
- Embeddings-based retrieval
- Role-based access control (RBAC)
- PII redaction support
- Safe handling of irrelevant queries
- Retrieval quality evaluation with a golden dataset

---

## Example Queries

### Relevant

- How many PTO days do employees get?
- Can PTO be carried over?
- How long is parental leave?
- How many sick leave days are given?
- How many days can employees work remotely?

### Safely Rejected as Irrelevant

- What is the company stock price?
- Who is the CEO?
- Tell me a joke

---

## Technology Stack

- Python
- Gradio
- Sentence Transformers
- NumPy
- Scikit-learn

---

## How It Works

1. Load or ingest HR content  
2. Apply semantic chunking and structure optimization  
3. Tag content with metadata and taxonomy  
4. Generate embeddings for retrieval  
5. Apply governance controls such as RBAC and PII filtering  
6. Retrieve relevant information for grounded responses  
7. Evaluate performance using a labeled question set  

---

## Project Structure

```text
hr-ai-content-system/
├── app.py
├── requirements.txt
├── README.md
├── pipeline/
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
---

## Why This Project Matters

This project demonstrates:

- AI-ready content engineering
- retrieval-augmented knowledge system design
- metadata and taxonomy thinking
- governance-aware AI workflows
- evaluation-driven AI development

## Important Note

This project is a prototype/demo build created to showcase AI-ready content processing, governance-aware retrieval, and enterprise-style knowledge system design.

---

## 🔗 Links & Attribution

### 🌐 Live Demo
[![Live Demo](https://img.shields.io/badge/Demo-HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/Chaitanya-Sanagana/hr-ai-content-system)

### 👤 Author
**Chaitanya Sanagana**
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Chaitanya-Sanagana)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chaitanya-sai-sanagana-8a1827263)