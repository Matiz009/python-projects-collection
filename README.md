# Python Projects Collection

Python practice projects: REST APIs with Flask and FastAPI, an LLM chatbot, web scraping and data cleaning.

## Projects

| Folder | What it is |
|---|---|
| [`flask-tasks-api/`](flask-tasks-api/) | Hardened Flask REST API for tasks: SQLAlchemy + Alembic, API-key auth, validation, rate limiting, tests, Docker and Vercel config. See its own README. |
| [`flask/`](flask/) | Simple Flask app with static pages, user routes and a SQLite-backed tasks API |
| [`fastapi/`](fastapi/) | Small FastAPI "Book API" with in-memory CRUD on books |
| [`chatbot-gpt/`](chatbot-gpt/) | Command-line chatbot using the Grok API via the OpenAI-compatible client, with pytest tests |
| [`chatbot/`](chatbot/) | Chatbot notebook |
| [`data-scrapping/`](data-scrapping/) | Web-scraping notebooks |
| `campus_store_sales*.csv` | Raw and cleaned sample sales data (TODO: link the notebook or script that produced the clean file) |

## Tech stack

Python · Flask · FastAPI · Pydantic · SQLAlchemy · Jupyter · pytest

## Getting started

Each folder is standalone. For example:

```bash
cd fastapi
pip install -r requirements.txt
uvicorn main:app --reload
```

```bash
cd chatbot-gpt
pip install -r requirements.txt
python chatbot.py
```

For setup and environment variables, see each sub-project's README (`flask-tasks-api/.env.example`).

## Author

**Mati ul Rehman**: [github.com/Matiz009](https://github.com/Matiz009)
