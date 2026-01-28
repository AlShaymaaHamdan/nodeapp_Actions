# Node.js App CI/CD with GitHub Actions

> This repository demonstrates a learning project for automating Docker builds and deployment using GitHub Actions.

---

## Overview

This workflow automatically:

1. Checks out the repository.  
2. Logs in to Docker Hub using GitHub secrets.  
3. Extracts metadata for the Docker image.  
4. Builds and pushes the Docker image to Docker Hub (`shaymaa12/nodeapp_actions:latest`).

> ⚠️ This project is for learning and practice. It is not production-ready.

---

## Workflow

- **Build & Push Docker Image:**  
  - Triggered on every `push` to the repository.  
  - Uses official GitHub Actions for Docker login, metadata extraction, and image build/push.

---

## Key Technologies

- GitHub Actions (CI/CD)  
- Docker  
- Docker Hub  

---

## Usage

1. Store Docker Hub credentials as GitHub secrets: `DOCKERHUB_USERNAME` and `DOCKERHUB_TOKEN`.  
2. Push code to trigger the workflow and automatically build and push the Docker image.

