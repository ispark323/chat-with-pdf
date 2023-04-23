# Chat with PDF

## Setup

```
python3 -m venv env && source env/bin/activate
pip install -r requirements.txt
export OPENAI_API_KEY=
```

## Ingest

Put a PDF file in docs folder and run below.

```
python3 ingest.py
```

## Run

```
uvicorn main:app --reload --port 9000
```