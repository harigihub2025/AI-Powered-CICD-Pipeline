# AI-Powered CI/CD Pipeline with Monitoring

## Project Overview
This project demonstrates a complete DevOps CI/CD pipeline using Jenkins, Docker, Prometheus, Grafana, and Node Exporter.

## Technologies Used
- Jenkins
- Git & GitHub
- Docker
- Docker Compose
- Nginx
- Prometheus
- Grafana
- Node Exporter
- Linux (Ubuntu)
- AWS EC2

## Pipeline Flow
1. Developer pushes code to GitHub
2. Jenkins pulls the latest code
3. Docker image is built
4. Old container is removed
5. New container is deployed
6. Prometheus collects metrics
7. Grafana visualizes metrics
8. Email alerts are sent automatically

## Features
- Automated CI/CD
- Docker Container Deployment
- Infrastructure Monitoring
- CPU & Memory Monitoring
- Email Alerts
- Node Exporter Integration

## Ports
- Jenkins : 8080
- Application : 8081
- Grafana : 3000
- Prometheus : 9090
- Node Exporter : 9100

## Monitoring Stack
- Prometheus
- Grafana
- Node Exporter

## Future Improvements
- Kubernetes Deployment
- Terraform Automation
- Slack Notifications
- AI-based Log Analysis
