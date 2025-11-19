# Clark University Cloud Computing Final Project

## Project Overview
This is a cloud computing course project demonstrating:
- AWS EC2 deployment
- Docker containerization
- Node.js web application
- DevOps practices

## Live Demo
Access the application at: http://98.92.78.49:9981/clarku-demo

## Technologies Used
- AWS EC2
- Docker
- Node.js & Express.js
- Linux (Amazon Linux 2023)

## Setup Instructions
```bash
git clone https://github.com/vamsireddy1998/cloud-computing-final-project.git
cd cloud-computing-final-project
npm install
node app.js
```

## Docker Deployment
```bash
docker build -t clarku-app .
docker run -p 9981:9981 clarku-app
```

## Project Features
- Professional Clark University landing page
- Containerized deployment
- Cloud infrastructure on AWS

## Course: Cloud Computing
**Clark University** - Demonstrating modern cloud technologies.
