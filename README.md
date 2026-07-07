**🩺 AI Doctor Backend (RAG Powered)

An AI-powered medical assistant backend built with FastAPI, Groq Llama 4, Whisper, and ChromaDB. It supports symptom analysis, medical image understanding, voice transcription, medical report analysis, and Retrieval-Augmented Generation (RAG) using custom medical PDFs.

**Features

--💬 AI symptom analysis using Groq Llama 4
--🖼️ Medical image analysis
--🎤 Voice-to-text using Whisper
--🔊 Text-to-speech responses
--📄 Medical report (PDF/Image) analysis
--📚 RAG-powered medical knowledge base with ChromaDB
--🌍 Multilingual support (English, Hindi, Spanish, French, etc.)
--📰 Latest health news API
--👤 User-specific document indexing
--🔧 Admin PDF upload & management

##Tech Stack
-FastAPI
-Groq (Llama 4 + Whisper)
-LangChain
-ChromaDB
-Hugging Face Embeddings
-PyMuPDF
-gTTS

##Project Structure
main.py                  # FastAPI backend
brain_of_the_doctor.py   # AI response generation
voice_of_the_patient.py  # Speech-to-text
voice_of_the_doctor.py   # Text-to-speech
rag_pipeline.py          # RAG pipeline
ingest_pdfs.py           # PDF ingestion

##Setup
git clone <repository-url>
cd <repository-folder>

pip install -r requirements.txt

##Run the server:

uvicorn main:app --reload

##API will be available at:

http://localhost:8000

Interactive API Docs:

http://localhost:8000/docs

##License

This project is for educational and research purposes only and is not a substitute for professional medical advice or diagnosis.
