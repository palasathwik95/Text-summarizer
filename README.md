# Summarizer-HF
Text Summarizer App - Transformer Minor Project (using HuggingFace &amp; FastAPI)

## Run locally

Install the dependencies, then start FastAPI from this directory:

```powershell
python -m pip install -r requirements.txt
python -m uvicorn app:app --reload
```

Open http://127.0.0.1:8000/ in your browser. If `saved_summary_model` is absent, the app downloads and uses `t5-small` automatically.
