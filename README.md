# AI Story Teller

A Streamlit-based AI filmmaking/story assistant powered by OpenRouter. It helps users develop a story and download it as a PDF.

## Run locally

1. Install Python 3.10 or newer.
2. Create and activate a virtual environment.
3. Install dependencies with `pip install -r requirements.txt`.
4. Create a `.env` file in the project root containing `OPENROUTER_API_KEY=your_openrouter_api_key`.
5. Run `streamlit run app.py`.

## Deploy on Streamlit Community Cloud

1. Push this project to a GitHub repository.
2. Create an app from that repository in Streamlit Community Cloud.
3. Set the main file path to `app.py`.
4. In the app's **Settings → Secrets**, add `OPENROUTER_API_KEY = "your_openrouter_api_key"`.

Never commit `.env` or `.streamlit/secrets.toml`. The `.gitignore` file excludes them.
