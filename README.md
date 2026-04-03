🔐 Vaultwarden Self-Hosted Deployment

Deployed a self-hosted Bitwarden-compatible password manager using Docker Compose with secure reverse proxy setup.
Key features:
Containerized Vaultwarden service
Nginx reverse proxy with HTTPS (wildcard SSL)
Environment-based secret management (.env)
Healthchecks and auto-restart policies
Internal Docker networking (no direct container exposure)
Persistent storage for encrypted vault data
Tech stack:
Docker / Docker Compose
Nginx
TLS/SSL (wildcard certificates)
Linux

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
