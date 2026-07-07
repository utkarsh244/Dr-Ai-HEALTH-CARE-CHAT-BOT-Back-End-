# 🩺 AI Doctor Backend (RAG Powered)

An AI-powered medical assistant backend built with **FastAPI**, **Groq Llama 4**, **Whisper**, and **ChromaDB**.

## Features

- 💬 AI symptom analysis using Groq Llama 4
- 🖼️ Medical image analysis
- 🎤 Voice-to-text using Whisper
- 🔊 Text-to-speech responses
- 📄 Medical report (PDF/Image) analysis
- 📚 RAG-powered medical knowledge base with ChromaDB
- 🌍 Multilingual support
- 📰 Latest health news API
- 👤 User-specific document indexing
- 🔧 Admin PDF upload & management

## Tech Stack

- FastAPI
- Groq (Llama 4 + Whisper)
- LangChain
- ChromaDB
- Hugging Face Embeddings
- PyMuPDF
- gTTS

## Project Structure

```text
main.py                  # FastAPI backend
brain_of_the_doctor.py   # AI response generation
voice_of_the_patient.py  # Speech-to-text
voice_of_the_doctor.py   # Text-to-speech
rag_pipeline.py          # RAG pipeline
ingest_pdfs.py           # PDF ingestion
```

## Setup

```bash
git clone <repository-url>
cd <repository-folder>

pip install -r requirements.txt
```

## Run

```bash
uvicorn main:app --reload
```

API:
```
http://localhost:8000
```

Swagger Docs:
```
http://localhost:8000/docs
```
