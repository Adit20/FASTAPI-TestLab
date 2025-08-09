<<<<<<< HEAD
# FASTAPI-TestLab
This is serves as a lab to get famaliar with FAST Api
=======

# Lab 01 — Hello FastAPI

**Goal:** Warm up with a tiny service.

## Run locally
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
# open http://localhost:8000/docs
```

## With Docker
```bash
docker build -t lab01-hello .
docker run -p 8000:8000 lab01-hello
```
>>>>>>> 0aeb8ba (sample commit done using CLI for FastAPI App)
