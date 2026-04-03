# 🔐 Bitwarden Self-Hosted (Docker + Nginx)

## 📌 Overview

This project demonstrates deployment of a self-hosted Bitwarden (Vaultwarden) instance using Docker and Nginx as a reverse proxy.

## 🧱 Architecture

* Vaultwarden (Bitwarden backend)
* Docker Compose
* Nginx reverse proxy
* Persistent storage (volumes)

## ⚙️ Tech Stack

* Docker / Docker Compose
* Nginx
* Linux

## 🚀 Features

* Self-hosted password manager
* Secure reverse proxy setup
* Environment-based configuration
* Backup script for data persistence

## 📦 Deployment

```bash
git clone https://github.com/yourusername/bitwarden-selfhosted-docker.git
cd bitwarden-selfhosted-docker
cp .env.example .env
docker-compose up -d
```

## 🔐 Security Notes

* HTTPS should be enabled via reverse proxy (Let's Encrypt recommended)
* Environment variables used for secrets
* Access restricted via firewall rules

## 💾 Backup

```bash
bash scripts/backup.sh
```

## 📊 Result

* Fully working self-hosted Bitwarden instance
* Secure and reproducible deployment

## 🎯 Purpose

This project demonstrates real-world DevOps practices:

* Service containerization
* Reverse proxy configuration
* Secure service exposure
* Data persistence and backup
