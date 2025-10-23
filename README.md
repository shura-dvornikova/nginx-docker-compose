# 🚀 Nginx Docker Compose Project

This project demonstrates how to deploy a lightweight **Nginx** web server using **Docker Compose**.  
The container automatically serves static HTML content from a local directory and includes a basic healthcheck for monitoring container status.

---

## 🧩 Features
- 🐳 Containerized Nginx web server (`nginx:alpine`)
- Serves static files from a mounted `html/` directory
- Custom configuration via `nginx/conf.d/default.conf`
- Healthcheck endpoint `/health`
- Easily deployable to any Linux VPS or cloud instance

---

## 🗂 Project Structure

nginx-docker-compose/
├─ docker-compose.yml
├─ html/
│ └─ index.html
└─ nginx/
└─ conf.d/
└─ default.conf

---

## ⚙️ How to Run Locally

1️⃣ **Clone the repository**

git clone https://github.com/<your-username>/nginx-docker-compose.git
cd nginx-docker-compose

2️⃣ **Start the container**
docker compose up -d

3️⃣ **Open in your browser**
http://localhost:8080
