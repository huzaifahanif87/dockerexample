# 🚀 Simple Flask App (Dockerized)

This is a minimal **Flask web app** wrapped inside a **Docker container**.  
Purpose: To demonstrate containerizing a Python Flask app using Docker.

## 🔥 Tech Stack

- 🐍 **Flask** (Python)
- 🐳 **Docker**
- 🌐 **HTML** (Single-page template)

## 📦 How to Run

### ➡️ Run without Docker

```bash
pip install Flask
python app.py
 ```
### ➡️ Run with Docker

```bash
docker build -t flask-docker-demo .
docker run -d -p 5000:5000 flask-docker-demo
 ```
