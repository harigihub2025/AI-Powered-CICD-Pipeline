# 🚀 AI-Powered CI/CD Pipeline

## 📌 Project Overview
This project demonstrates a complete AI-powered CI/CD pipeline using Jenkins, Docker, Prometheus, Grafana, and Node Exporter.

The pipeline automatically builds, deploys, monitors, and sends email alerts for the application.

---

## 🛠️ Tech Stack

- Git & GitHub
- Jenkins
- Docker
- Docker Compose
- Nginx
- Prometheus
- Grafana
- Node Exporter

---

## 📂 Project Structure

```
AI-Powered-CICD/
│
├── app/
├── docker/
├── docs/
├── jenkins/
├── monitoring/
├── scripts/
├── terraform/
└── README.md
```

---

## ⚙️ CI/CD Workflow

1. Developer pushes code to GitHub.
2. Jenkins automatically triggers the pipeline.
3. Docker image is built.
4. AI Web Application is deployed.
5. Docker Compose starts:
   - Prometheus
   - Grafana
   - Node Exporter
6. Prometheus collects metrics.
7. Grafana visualizes metrics.
8. Email alerts are sent through SMTP.

---

## 📊 Monitoring

- Prometheus Metrics
- Grafana Dashboard
- Node Exporter
- Email Alerts

---

## 🏗️ Architecture Diagram

See:

```
docs/architecture-diagram
```

---

## 📷 Screenshots

- Jenkins Pipeline Success
- Grafana Dashboard
- Prometheus Targets
- Email Alert
- Architecture Diagram

---

## 👨‍💻 Author

Hariharan
