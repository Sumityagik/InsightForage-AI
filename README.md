# 🧠 InsightForge AI

>An Agentic AI system for intelligent information extraction using LangChain, Groq, KeyBERT and spaCy.

> An AI-powered research document analysis notebook that performs **Text Summarization**, **Keyword Extraction**, and **Named Entity Recognition (NER)** using modern NLP techniques and LangChain tools.

![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)
![LangChain](https://img.shields.io/badge/LangChain-Agentic_AI-green)
![SentenceTransformers](https://img.shields.io/badge/SentenceTransformers-Embeddings-orange)
![KeyBERT](https://img.shields.io/badge/KeyBERT-Keyword_Extraction-yellow)
![spaCy](https://img.shields.io/badge/spaCy-NER-brightgreen)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-red)

---

# 📖 About the Project

InsightForge AI is an intelligent NLP notebook developed as part of my Agentic AI learning journey.

The notebook combines multiple Natural Language Processing techniques into a modular pipeline capable of understanding research papers and large text documents.

Instead of using individual NLP models separately, the project follows an agent-inspired architecture where specialized tools work together to generate meaningful insights from text.

---

# ✨ Features

- 📄 Automatic Text Summarization
- 🔑 Keyword Extraction using KeyBERT
- 👤 Named Entity Recognition (NER)
- 🧠 Sentence Embeddings using Sentence Transformers
- ⚡ Modular AI Tool Design
- 🤖 LangChain Tool Integration
- 📊 Structured AI Analysis Report
- 🚀 Optimized Model Loading with Caching

---

# 🏗️ Project Workflow

```text
User Input
      │
      ▼
Text Preprocessing
      │
      ▼
Embedding Model
(Sentence Transformers)
      │
      ├───────────────┐
      ▼               ▼
Keyword Tool      NER Tool
(KeyBERT)          (spaCy)
      │               │
      └──────┬────────┘
             ▼
 Summarization Tool
(BART Transformer)
             │
             ▼
Structured AI Report
```

---

# 🛠️ Technologies Used

- Python
- Google Colab
- LangChain
- Sentence Transformers
- Hugging Face Transformers
- KeyBERT
- spaCy
- PyTorch
- NumPy

---

# 📂 Notebook Structure

The notebook is organized into multiple sections:

1. Environment Setup
2. Installing Dependencies
3. Loading AI Models
4. Model Registry
5. Building LangChain Tools
6. Keyword Extraction Tool
7. Named Entity Recognition Tool
8. Text Summarization Tool
9. AI Orchestrator
10. Testing Individual Tools
11. Final Integrated Analysis

---

# 🚀 How to Run

## Step 1

Open the notebook in **Google Colab**.

---

## Step 2

Run every cell sequentially from top to bottom.

---

## Step 3

Install all required dependencies when prompted.

---

## Step 4

Wait for the models to download during the first execution.

The notebook automatically caches loaded models to reduce loading time in future executions.

---

## Step 5

Provide any research paper, article, or long text as input.

Example:

```text
Google DeepMind recently introduced Gemini, a multimodal AI model...
```

---

## Step 6

The notebook generates:

- 📄 Summary
- 🔑 Keywords
- 👤 Named Entities

---

# 📊 Example Output

```text
==================================================
🧠 InsightForge AI Analysis Report
==================================================

📄 SUMMARY
----------------------------
...

🔑 KEYWORDS
----------------------------
Google DeepMind
Gemini
Deep Learning
Transformer

👤 NAMED ENTITIES
----------------------------
Google DeepMind (Organization)
Demis Hassabis (Person)
London (Location)
```

---

# 📦 Requirements

```
langchain
langchain-core
sentence-transformers
transformers
torch
keybert
spacy
numpy
pandas
```

Download the spaCy English model:

```bash
python -m spacy download en_core_web_sm
```

---

# 🧠 What I Learned

This project helped me understand both NLP fundamentals and how to structure AI systems using reusable components.

Key concepts I learned include:

- Sentence Embeddings
- Semantic Similarity
- Keyword Extraction
- Named Entity Recognition
- Transformer-based Summarization
- LangChain Tools
- Prompt Engineering
- AI Model Registry Pattern
- Modular Software Design
- Model Caching
- AI Workflow Orchestration

Beyond implementing individual NLP models, I learned how to design a modular AI pipeline where specialized tools collaborate to analyze text efficiently.

---

# 📈 Future Improvements

- Flask Web Application
- ChatGPT-style User Interface
- PDF Upload Support
- DOCX Upload Support
- Research Paper Analyzer
- Multi-document Analysis
- AI Chat Interface
- Export Analysis as PDF
- REST API Support
- Docker Deployment

---

# 🎯 Project Objective

The objective of this project is to explore how multiple NLP techniques can be integrated into a unified AI workflow capable of analyzing unstructured text efficiently.

Rather than focusing on a single NLP task, InsightForge AI demonstrates how modular AI components can work together to generate richer insights from textual data.

---

# 👨‍💻 Author

**Sumit Yagik**

B.Tech Computer Science & Engineering

AI & Machine Learning Enthusiast

Passionate about NLP, Generative AI, and Agentic AI Systems.

---

⭐ If you found this project interesting, consider giving it a star!
