# Dockerized Python Application

## Description
This project uses the python:3.12-slim Docker image. It prints the current Python version and current date/time when the container starts.

## Build Docker Image

```bash
docker build -t python-app .
```

## Run Docker Container

```bash
docker run python-app
```

## Sample Output

```text
Python Version: 3.12.x
Current Date & Time: 2026-06-13
```