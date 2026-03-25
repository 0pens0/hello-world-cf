# Hello World Python Application

A simple Flask Hello World application for Cloud Foundry deployment.

## Run Locally

```bash
pip install -r requirements.txt
python app.py
```

## Deploy to Cloud Foundry

```bash
cf push
```

## Endpoints

- `/` - Returns "Hello World from Cloud Foundry!"
- `/health` - Health check endpoint

## Repository

GitHub: https://github.com/0pens0/hello-world-cf
