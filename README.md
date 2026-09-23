# AI Explorer

Single-folder Flask + Gemini chatbot for Render.

## Render
Build command: `pip install -r requirements.txt`
Start command: `gunicorn app:app`

Add Environment Variables:
- `GEMINI_API_KEY` = your Gemini API key
- `GEMINI_MODEL` = `gemini-2.5-flash` (optional)

The Gemini key is not stored in `app.py`.
