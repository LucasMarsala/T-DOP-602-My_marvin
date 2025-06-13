# Jenkins Automation Platform

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/989063c2d88a4aeb912b9f31138b4869)](https://www.codacy.com/gh/LucasMarsala/T-DOP-600-My_marvin/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=LucasMarsala/T-DOP-600-My_marvin&amp;utm_campaign=Badge_Grade)

This repository contains a Jenkins automation platform designed to automate the cloning of student repositories.

## ⚠️ Security Notice

**IMPORTANT**: This is a development environment setup. The default credentials (admin/admin) should **NEVER** be used in production environments.

## 🛠️ Prerequisites

- Docker version 20.10 or higher
- Docker Compose version 1.29.2 or higher

## 🚀 Quick Start

1. Clone the repository:
```bash
git clone https://github.com/LucasMarsala/T-DOP-602-My_marvin.git
cd T-DOP-602-My_marvin
```

2. Build and start the containers:
```bash
docker compose up --build
```

3. Access Jenkins:
- URL: `http://localhost:8080`
- Username: `admin`
- Password: `admin`

## 📁 Project Structure

```
.
├── configuration/     # Jenkins configuration files
├── jobs/            # Jenkins job definitions
├── plugins/         # Jenkins plugins
├── Dockerfile       # Jenkins container definition
├── compose.yml      # Docker Compose configuration
└── .gitignore      # Git ignore rules
```

## 🛠️ Technologies Used

- Groovy (71.8%)
- Dockerfile (28.2%)

## 🔧 Features

- Automated repository cloning
- Jenkins CI/CD pipeline setup
- Docker containerization
- Custom plugin configuration

---
⭐ Don't forget to star this repository if you found it useful!
