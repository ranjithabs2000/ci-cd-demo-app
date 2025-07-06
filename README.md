nano README.md# CI/CD Pipeline Project

## 📁 Project Structure

```
ci-cd-demo-app/
├── Dockerfile
├── pom.xml
├── README.md
├── src/
│   └── main/java/
├── target/
```

## 🚀 Tools Used
- AWS EC2 (Ubuntu)
- Jenkins
- Maven
- Docker
- GitHub

## ✅ What This Project Does

- Pulls Java code from GitHub
- Builds with Maven using Jenkins
- Builds Docker image
- Pushes Docker image to Docker Hub

## 🔧 How to Run Locally

### 1. Clone this project

```
git clone https://github.com/ranjithabs2000/ci-cd-demo-app.git
cd ci-cd-demo-app
```

### 2. Build using Maven

```
mvn clean package
```

### 3. Build and Run Docker Image

```
docker build -t ci-cd-demo-app .
docker run -d -p 8080:8080 ci-cd-demo-app
```
