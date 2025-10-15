# Lab 08: Automate a Spring Boot and React App using Jenkins for CI/CD

## Objective
The objective of this lab is to automate the build, test, and deployment process of a full-stack web application using Jenkins.  
The application consists of a Spring Boot backend and a React frontend.  
The Jenkins pipeline integrates with GitHub to continuously build, test, and simulate deployment whenever changes are pushed.

## Tools / Technologies
- Jenkins
- Git and GitHub
- Java (JDK 17 or higher)
- Spring Boot (Maven)
- Node.js and npm
- React.js
- Docker (optional)
- Command Line / Terminal

## Prerequisites
- Jenkins is installed and running on the system.
- Java, Maven, Node.js, and npm are installed and configured.
- GitHub repository contains both backend and frontend source code.
- Jenkins has access to Git and the GitHub repository.
- Optional: Docker installed for containerized deployment.

## Steps / Commands

### Step 1: Clone the Repository
```bash
git clone https://github.com/viswanath401/lab8.git
cd lab8
