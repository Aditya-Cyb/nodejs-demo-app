# Task 1: Node.js CI/CD Pipeline using GitHub Actions

## Project Overview

This project demonstrates a CI/CD workflow for a Node.js web application using GitHub Actions, Docker, Docker Hub, and Render.

The application is developed using Node.js and Express, containerized using Docker, and integrated with a GitHub Actions pipeline that automatically runs on every push to the `main` branch.

## CI/CD Workflow

**Node.js Application**  
↓  
**GitHub Repository**  
↓  
**GitHub Actions**  
↓  
**Install Dependencies**  
↓  
**Run Tests**  
↓  
**Build Docker Image**  
↓  
**Push Image to Docker Hub**  
↓  
**Deploy on Render**  
↓  
**Live Web Application**

## Technologies Used

- Node.js & Express
- Git & GitHub
- GitHub Actions
- Docker
- Docker Hub
- Render

## Key Features

- Automated CI pipeline using GitHub Actions
- Automated dependency installation and testing
- Docker image creation
- Docker Hub image publishing
- Cloud deployment using Render
- Publicly accessible Node.js application

## Docker Image

**Repository:** `adityadev02/nodejs-demo-app`

**Tag:** `latest`

## Live Application

[🚀 View Live Application](https://nodejs-demo-app-z66j.onrender.com)

Click the link above to view the deployed Node.js application.

## Documentation

Detailed implementation steps, configuration, screenshots, deployment verification, and CI/CD workflow are available in the project documentation.

[📄 View Task 1 Documentation](documentation/Task_1_CI_CD_Documentation.docx)

## Project Structure

- `app.js` — Node.js application
- `package.json` — Project configuration and dependencies
- `package-lock.json` — Dependency lock file
- `Dockerfile` — Docker image configuration
- `README.md` — Project documentation summary
- `.github/workflows/main.yml` — GitHub Actions CI/CD workflow
- `documentation/Task_1_CI_CD_Documentation.docx` — Detailed Task 1 documentation

## Result

The Node.js application was successfully containerized using Docker, integrated with GitHub Actions, pushed to Docker Hub, and deployed on Render.

The deployed application is publicly accessible through the Live Application link above.
