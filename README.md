# Prime Assist Chatbot

Prime Assist Chatbot is a Python chatbot project using LangChain, Groq, Flask, and common machine-learning/data tooling. The repository is intended to provide an assistant-style chat experience with configurable environment variables and local development support.

## Features

- Python chatbot application structure
- LangChain and Groq integration dependencies
- Flask dependency for serving a web interface or API
- Data and ML utilities including scikit-learn, NumPy, PyTorch, datasets, NLTK, and matplotlib

## Setup

1. Create and activate a virtual environment:

```bash
python -m venv .venv
.venv\Scripts\activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Copy the example environment file:

```bash
copy .env.example .env
```

4. Fill in the required values in `.env`.

5. Run the application using the main Python entrypoint for the project.

## Environment Variables

See `.env.example` for the expected configuration values. Never commit real API keys, tokens, local `.env` files, logs, or virtual environments.

## Repository Hygiene

This project intentionally keeps secrets and generated files out of git through `.gitignore`. Add setup notes, screenshots, and exact run commands as the application structure becomes final.
