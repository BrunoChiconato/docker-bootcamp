# Descomplicando o Docker Course - Exercises & Projects Repository

A comprehensive collection of exercises and projects developed as part of the **"Descomplicando o Docker"** course by LinuxTips. This repository serves as a centralized hub for all hands-on learning materials, from Docker fundamentals to advanced container orchestration.

[![Course Progress](https://img.shields.io/badge/Progress-7%2F7%20Days-brightgreen)][progress-url]
[![Docker](https://img.shields.io/badge/Docker-Supported-blue?logo=docker)][docker-url]

## Table of Contents

- [Highlights](#highlights)
- [Course Overview](#course-overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [File Structure](#file-structure)
- [Daily Breakdown](#daily-breakdown)
- [Acknowledgments](#acknowledgments)

## Highlights

- ✅ **Complete 7-day Docker curriculum** covering fundamentals to advanced orchestration.
- 🛡️ **Security-focused learning** with Distroless images and vulnerability management.
- 🔗 **Networking mastery** with comprehensive container communication strategies.
- 📦 **Volume management** for persistent data handling.
- 🎼 **Multi-container orchestration** using Docker Compose.
- 🚀 **Introduction to Kubernetes and Hashicorp Nomad** for cloud-native scalability.
- 💡 **Hands-on exercises** with real-world applications.
- 📚 **Best practices** for production-ready containerization.

## Course Overview

This course transforms complex Docker concepts into easy-to-understand, practical knowledge. The curriculum is structured into three main learning pillars:

### 1. Fundamentals and Best Practices
- **Docker Fundamentals**: Master core concepts and understand the importance of containers in application modernization.
- **Image Creation and Management**: Excel with Dockerfiles and optimize images for maximum efficiency.
- **Volume and Storage Management**: Maintain persistent data effectively and reliably.

### 2. Security and Networking
- **Container Security**: Learn to identify and fix vulnerabilities, creating secure images with Distroless.
- **Docker Networking**: Configure and manage networks between containers with ease and security.

### 3. Orchestration and Scalability
- **Docker Compose Orchestration**: Automate and manage multi-container applications efficiently.
- **Introduction to Kubernetes and Hashicorp Nomad**: Take first steps in advanced container orchestration.

## Prerequisites

Before starting with this repository, ensure you have:

- **Docker Engine** (version 20.10 or higher).
- **Docker Compose** (version 2.0 or higher).
- **Basic terminal/command line knowledge**.
- **Text editor or IDE**.
- **Git** for version control.

### System Requirements

- **Operating System**: Linux, macOS, or Windows 10/11 with WSL2.
- **RAM**: Minimum 4GB (8GB recommended).
- **Storage**: At least 10GB free space.
- **Network**: Internet connection for pulling images.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/BrunoChiconato/docker-bootcamp.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd docker-bootcamp
   ```

3. **Verify Docker installation**:
   ```bash
   docker --version
   docker-compose --version
   ```

## File Structure

```
.
├── README.md
├── .gitignore
├── day-02/
│   ├── Dockerfile.1
│   ├── Dockerfile.2
│   ├── Dockerfile.3
│   ├── Dockerfile.4
│   ├── Dockerfile.5
│   ├── Dockerfile.5.Multistage
│   ├── Dockerfile.6
│   ├── Dockerfile.7
│   ├── hello.go
│   └── index.html
├── day-03/
│   └── giropops-senhas/
│       ├── static/
│       ├── templates/
│       ├── .deepsource.toml
│       ├── app.py
│       ├── Dockerfile
│       ├── LICENSE
│       ├── requirements.txt
│       └── tailwind.config.js
├── day-06/
│   ├── docker-compose.yaml
│   ├── docker-compose-1.yaml
│   ├── docker-compose-2.yaml
│   └── docker-compose-3.yaml
└── day-07/
    └── kind/
        └── kind-cluster.yaml
```

## Daily Breakdown

### Day 1 – Docker Fundamentals and First Steps
Start your container journey on the right foot. This module distills Docker complexity into simple language, making it easy for complete beginners to understand containers and their revolutionary impact.

### Day 2 – Mastering Dockerfiles and Image Management
Become a Docker Image Artist! Learn to create, optimize, and manage Docker images professionally, saving time and resources in future projects.

### Day 3 – Security and Image Optimization with Distroless
Strengthen Your Infrastructure. Create secure and efficient Docker images, identify and fix vulnerabilities, and optimize applications using Distroless images.

### Day 4 – Managing Volumes and Storage
Master Container Storage! Eliminate storage problems by learning everything about Docker volumes and managing persistent data effectively.

### Day 5 – Docker Networking
Connect with Confidence! Networking doesn't have to be complicated. Learn to establish, manage, and optimize networks in Docker environments.

### Day 6 – Orchestration with Docker Compose
Orchestrate Your Containers like a Maestro! Take a giant leap in your career by mastering Docker Compose and managing multi-container applications.

### Day 7 – Introduction to Kubernetes and Hashicorp Nomad
Grow in the Modern Orchestration Era! Prepare for the next level in container orchestration with solid introductions to industry-leading tools.

## Acknowledgments

- **LinuxTips** for creating and delivering this course.

[build-url]: #
[progress-url]: #
[docker-url]: https://www.docker.com/
[license-url]: LICENSE