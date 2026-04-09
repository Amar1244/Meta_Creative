# Meta_Creative

Streamlit app for generating Meta ad creatives with prompt building, feed/story generation, authentication, and activity tracking.

## Run locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Required secrets

Set these in your environment or Streamlit secrets:

- `GROQ_API_KEY`
- `FAL_API_KEY`
- `AUTH_COOKIE_KEY` (optional but recommended)

## Deploy on Streamlit

1. Push this folder to GitHub.
2. Create a new app on Streamlit Community Cloud.
3. Set `app.py` as the main file.
4. Add the required secrets in the Streamlit app settings.
