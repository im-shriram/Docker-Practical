# 🐳 Flask Docker App

A simple Flask web application containerized with Docker.

## 🚀 Quick Start

### Run with Docker Compose (Recommended)
```bash
docker compose up --build
```

### Run with Docker
```bash
docker build -t flask-app .
docker run -p 5000:5000 flask-app
```

### Run Locally
```bash
pip install -r requirements.txt
python app.py
```

📍 Open [http://localhost:5000](http://localhost:5000)

---

## 📁 Project Structure

```
├── app.py              # Flask application
├── templates/          # HTML templates
├── Dockerfile          # Container configuration
├── compose.yaml        # Docker Compose config
└── requirements.txt    # Python dependencies
```

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Flask** | Web framework |
| **Gunicorn** | Production WSGI server |
| **Docker** | Containerization |

---

<p align="center">
  Made with ❤️ for learning Docker
</p>
