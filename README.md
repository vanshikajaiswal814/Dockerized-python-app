# 🐳 Dockerized Python Hello World App

A simple Python application containerized using Docker and deployed via Docker Hub.

---

## 📌 Project Overview

This project demonstrates:

* Creating a basic Python application
* Dockerizing the application
* Running the container on an Ubuntu EC2 instance
* Pushing the Docker image to Docker Hub

---

## 🛠️ Tech Stack

* Python 3
* Docker
* Ubuntu (EC2 Instance)

---

## 📂 Project Structure

```
.
├── app.py
└── Dockerfile
```

---

## 🚀 How to Run the Application

### 🔹 Run locally (without Docker)

```bash
python3 app.py
```

---

### 🔹 Build Docker Image

```bash
docker build -t python-docker-app .
```

---

### 🔹 Run Docker Container

```bash
docker run python-docker-app
```

---

## 🌐 Docker Hub Image

You can pull the image directly from Docker Hub:

```bash
docker pull vanshikamod/python-docker-image
docker run vanshikamod/python-docker-image
```

---

## 📤 GitHub Repository

This repository contains the source code and Docker configuration for the application.

---

## ✨ Output

```
Hello from Dockerized Python App 🚀
```

---

## 📌 Author

Vanshika Jaiswal

---
