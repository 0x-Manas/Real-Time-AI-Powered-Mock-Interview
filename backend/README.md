# Backend - Real-Time AI-Powered Mock Interview

This backend is developed using FastAPI and handles:

- Speech-to-text conversion
- Semantic similarity analysis
- Interview response evaluation
- API communication with frontend
- Emotion analysis integration

---

## Technologies Used

- Python
- FastAPI
- PyTorch
- HuggingFace Transformers
- Whisper
- SentenceTransformers

---

## Main Functionalities

### Audio Processing
Converts user speech into text using OpenAI Whisper model.

### Semantic Similarity
Compares candidate answers with predefined answers using SentenceTransformer embeddings and cosine similarity.

### API Endpoints
Handles frontend requests and returns feedback scores in real-time.

---

## Models Used

- Whisper Base Model
- all-MiniLM-L6-v2 SentenceTransformer

---

## Run Backend

```bash
pip install -r requirements.txt
uvicorn main:app --reload
