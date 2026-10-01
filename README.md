# nodejs-demo-app

# Task 1: Node.js CI/CD Pipeline using GitHub Actions

## Project Overview

This project demonstrates a CI/CD workflow for a Node.js web application using GitHub Actions, Docker, Docker Hub, and Render.

The application is developed using Node.js and Express, containerized using Docker, and integrated with a GitHub Actions pipeline that automatically runs on every push to the `main` branch.

## CI/CD Workflow

text
Node.js Application
        ↓
      GitHub
        ↓
 GitHub Actions
        ↓
Install Dependencies
        ↓
     Run Tests
        ↓
   Build Docker Image
        ↓
   Push to Docker Hub
        ↓
   Deploy on Render
        ↓
Live Web Application
Technologies Used
Node.js & Express
Git & GitHub
GitHub Actions
Docker
Docker Hub
Render
Key Features
Automated CI pipeline using GitHub Actions
Automated dependency installation and testing
Docker image creation
Docker Hub image publishing
Cloud deployment using Render
Publicly accessible Node.js application
Docker Image

adityadev02/nodejs-demo-app:latest

Live Application

🚀 View Live Application

Click the link above to view the deployed Node.js application.

Documentation

Detailed implementation steps, configuration, screenshots, deployment verification, and CI/CD workflow are available in the project documentation.

📄 View Task 1 Documentation

Project Structure
nodejs-demo-app/
│
├── app.js
├── package.json
├── package-lock.json
├── Dockerfile
├── README.md
│
├── .github/
│   └── workflows/
│       └── main.yml
│
└── documentation/
    └── Task_1_CI_CD_Documentation.docx
Result

The Node.js application was successfully containerized using Docker, integrated with GitHub Actions, pushed to Docker Hub, and deployed on Render.

The deployed application is publicly accessible through the Live Application link above.
