# IRAA

A local, voice-first AI assistant: listens, thinks, remembers, and performs tasks.

## Status: Day 1 / 90 — Phase 1 (Core Voice Loop)

## Stack
- Python, FastAPI, SQLite
- faster-whisper (STT)
- Ollama — Llama 3 / Mistral / Qwen (LLM)
- sentence-transformers + ChromaDB/FAISS (memory)
- Piper TTS (voice output)
- Docker, GitHub

## Structure
```
backend/   # FastAPI app, API routes
voice/     # audio recording, mic input
llm/       # LLM calls, prompt handling
tts/       # text-to-speech
stt/       # speech-to-text
core/      # shared logic, config, orchestration
tests/     # tests
```

## Setup
```bash
python3 -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Run
(coming Day 2+)
