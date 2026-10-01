# Mohamed Amine Ghorbali

AI engineer. Most of my work is RAG and local LLM inference: systems that run on self-hosted models because the data can't leave the building. I also have a background in computer vision and LLM fine-tuning.

Software engineering degree (data science track) from ESPRIT, Tunisia.

## Work

My internship code isn't public, so here is what it was:

- **Solvinya Group:** three microservices for an HR/recruitment platform, all on locally hosted LLMs:
  - a hybrid RAG policy assistant (BM25 + dense retrieval, RRF fusion, cross-encoder re-ranking, 86.7% Recall@5)
  - an async resume parser (FastAPI + Celery)
  - a real-time voice interview agent (faster-whisper, Silero VAD, Piper TTS over WebSocket/WebRTC)
- **Confledis:** LLM chatbot and backend services for a teleconsultation platform (Django REST, AWS, React/Ionic).

## Public projects

**[analyst-assistant-ai](https://github.com/Aethelios/analyst-assistant-ai)**
Local RAG app for asking questions about CSV, PDF, DOCX and TXT files. LangChain, ChromaDB, Hugging Face models on CPU (GGUF), Streamlit UI. Answers cite their sources, and the LLM can return chart specs that get rendered with Matplotlib.

**[PneumaTect](https://github.com/rouaaguesmi1/PneumaTect)**
Team project at ESPRIT (repo is on a teammate's account). Pulmonary nodule detection in CT scans with a 3D U-Net + CBAM, 3D CNN classification, and a FastAPI inference service behind a Laravel UI. I was project manager and one of the data scientists.

**[distilbert-reproduction](https://github.com/Aethelios/distilbert-reproduction)**
Knowledge distillation from BERT to a 6-layer student in PyTorch (MLM + cross-entropy + cosine losses). The student is faster but far less accurate than the paper's, and the results table in the repo shows it.

**[AI-Particle-Physics-Playground](https://github.com/Aethelios/AI-Particle-Physics-Playground)**
N-body gravity/electromagnetic simulation in NumPy and Pygame, with a DQN agent (PyTorch) that learns to avoid collisions.

**[mastering-rust-with-euler](https://github.com/Aethelios/mastering-rust-with-euler)**
Learning Rust through Project Euler.

## Stack

Python, PyTorch, Hugging Face, LangChain, LlamaIndex, ChromaDB, FAISS, FastAPI, Celery, Django, Docker, AWS. Also some JavaScript/React and PHP/Laravel.

## Contact

[Website](https://aethelios.github.io) · [LinkedIn](https://linkedin.com/in/mohamedamineghorbali) · mghorbali3@gmail.com
