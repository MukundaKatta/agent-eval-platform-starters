# Agent Eval Scorecard API

Tiny FastAPI service for scoring tool-using AI agent runs with an operational scorecard.

## Endpoints

- `GET /` returns service metadata
- `POST /score` accepts score dimensions and returns a rollout band

## Deploy Targets

Use this same artifact for Render, Railway, Koyeb, Fly.io, Paperspace, Lightning AI Studio, and Apify adaptation.

## Local Run

```bash
python -m pip install -r requirements.txt
uvicorn app:app --host 0.0.0.0 --port 8000
```

