# 🛡️ Sentinel Threat Hunter

A real-time cybersecurity dashboard to detect, enrich, and visualize suspicious network activity using Zeek, Kafka, Shodan, and the ELK stack.

## 🚀 Features
- Real-time traffic capture with Zeek
- Kafka-based log streaming
- Threat enrichment using Shodan API
- Live dashboards in Kibana
- Slack/email alert system
- Fully containerized with Docker

## 📦 Tech Stack
- Python, Kafka, Zeek, Elasticsearch, Kibana, Docker
- Shodan API for threat intel

## 🔧 Architecture
[Insert architecture diagram or link to one]

## 🧱 Modules
- `zeek/` – Captures and stores traffic logs
- `processor/` – Python pipeline for enrichment
- `alerts/` – Slack & email notification modules
- `dashboards/` – Pre-built Kibana visualizations

# Sentinel Stream

Real-time network traffic analysis system using Zeek and ELK stack.

## 🚀 Features
- Real-time packet capture and analysis
- Zeek-based traffic monitoring
- Elasticsearch for log storage
- Kibana dashboards

## ⚙️ Setup
```bash
git clone https://github.com/prabhakarsingour74/sentinel-stream.git
cd sentinel-stream
docker-compose up --build
```

## 🔧 Configuration
Configuration details in `config/` directory.