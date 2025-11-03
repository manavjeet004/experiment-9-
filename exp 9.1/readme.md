# Dockerize a React Application with Multi-Stage Build

## 🎯 Objective
Learn how to create a **production-ready Docker image** for a React application using a **multi-stage Docker build** to reduce image size and separate build dependencies from runtime.

---

## 🧰 Steps

### 1️⃣ Build the React App
If not already created:
```bash
npx create-react-app react-docker-app
cd react-docker-app
