# 🚀 Apache Traffic Control – CDN-in-a-Box Setup

This repository contains a Docker-based setup for running **Apache Traffic Control 8.0.2** using the `cdn-in-a-box` environment.

> ⚠️ Due to GitHub's file size limits, large required files are hosted externally via OneDrive.

---

## ✅ Prerequisites

Ensure the following software is installed on your machine:
- **Docker** version 20.10 or higher
- **Docker Compose** version 2.0 or higher (included with Docker)

### 🔍 Check Installed Versions

```bash
docker --version
docker compose version
```

Expected output should look like:

```bash
Docker version 20.10.x, build xxxxx
Docker Compose version v2.x.x
```

If Docker is not installed, download it from: https://docs.docker.com/get-docker/

## 📥 Step 1: Download the Repository Files

Download the full project (including large files) from OneDrive:

➡️ **[Download from OneDrive](https://infopercept-my.sharepoint.com/:u:/p/omv/ETAv77cF6AVBmb--I0OcD-4Bl2Y0sAwScpD3vUODEbkuMA?e=IG4s3j)**

After downloading, extract the ZIP file using the following commands in Debian WSL:

```bash
# Extract the ZIP file
unzip apache-trafficcontrol-8.0.2.zip

# Navigate to the extracted directory
cd apache-trafficcontrol-8.0.2/infrastructure/cdn-in-a-box
```

## 🛠️ Step 2: Build and Start the Project

Since you're already in the correct directory from Step 1, run:

```bash
docker compose build
docker compose up -d
```

## 📊 Step 3: Verify the Setup

Check running containers:

```bash
docker compose ps
```
