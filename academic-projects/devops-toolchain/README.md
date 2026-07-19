# DevOps Toolchain Project (DOP361 - Milestone 3)

**Course:** DOP361 - DevOps  
**Grade:** 72% (Distinction)  
**Date:** May 2026

---

## 📋 Project Overview

Complete DevOps toolchain implementation demonstrating Docker containerization, Chef configuration management, and Git collaboration workflows.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Docker** | Containerized Python application |
| **Chef** | Infrastructure as Code (Nginx setup) |
| **Git** | Version control and collaboration |
| **GitHub** | Repository hosting and branch management |

---

## 🐳 Docker Exercise

### Python Application
```python
print("=" * 50)
print("DevOps Practical Assignment")
print("Docker Container Running Successfully!")
print("Executed by: Tshiamo")
print("=" * 50)

FROM python:3.9-slim
WORKDIR /app
COPY app.py .
CMD ["python", "app.py"]

docker build -t tshiamo-python-app .
docker run tshiamo-python-app
