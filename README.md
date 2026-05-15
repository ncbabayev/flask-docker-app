# Flask Docker App

A simple Flask web application running inside a Docker container.

## Features
- Home page at `/`
- About page at `/about`

## Technologies
- Python 3.11
- Flask
- Docker

## How to run

```bash
docker build -t flask-docker-app .
docker run -p 5000:5000 flask-docker-app
```

Then open http://localhost:5000 in your browser.