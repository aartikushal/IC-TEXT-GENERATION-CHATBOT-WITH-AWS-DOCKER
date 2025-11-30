# 🤖 AI Story Generator API (Gemini 2.0 Flash)

A lightweight, high-performance **Text Generation API** built using
**FastAPI** and powered by **Google Gemini 2.0 Flash**. Fully
containerized with **Docker** and optimized for deployment on **AWS
EC2** for scalable cloud-based inference.

## 🚀 Features

-   Story Generator API\
-   FastAPI Backend\
-   Gemini 2.0 Flash\
-   Dockerized\
-   AWS EC2 Ready\
-   JSON-based Endpoint

## 🧩 Technology Stack

  Layer       Technology         Description
  ----------- ------------------ ----------------------
  Framework   FastAPI            REST API backend
  Model       Gemini 2.0 Flash   Google Generative AI
  Language    Python 3.11        Runtime
  Packaging   Docker             Containerization
  Cloud       AWS EC2            Deployment

## 🧱 Project Structure

    ├── app.py
    ├── requirements.txt
    ├── Dockerfile
    ├── supervisord.conf
    └── README.md

## ⚙️ Setup & Local Run

### Add API Key

export OPENAI_API_KEY="YOUR_API_KEY"

### Install Requirements

pip install -r requirements.txt

### Run API

python app.py

## 🐳 Docker Deployment

docker build -t gemini-story-api . docker run -d -p 8001:8001
gemini-story-api

## ☁️ AWS EC2 Deployment

Install Docker → Upload files → Build & run container → Open port 8001.

## 🌍 Live Endpoint

http://13.51.196.70:8002/docs

## 📚 Example Output

{ "story": "Once upon a time..." }

## 📄 License

MIT License © 2025
