# CI/CD Web Application Deployment using Jenkins

## 📌 Project Overview
This project demonstrates an end-to-end CI/CD pipeline where a Java web application
is automatically built and deployed to Apache Tomcat using Jenkins.

## 🔧 Tech Stack
- Git
- GitHub
- Jenkins
- Maven
- Apache Tomcat
- ngrok
- GitHub Webhooks

## 🔄 CI/CD Flow
1. Developer pushes code to GitHub
2. GitHub Webhook triggers Jenkins job
3. Jenkins pulls source code
4. Maven builds the application
5. WAR file is deployed to Tomcat
6. Application is accessible via browser

## ⚙️ Jenkins Configuration
- SCM: GitHub Repository
- Build Tool: Maven
- Deployment: Apache Tomcat
- Trigger: GitHub Webhook

## 🌐 Webhook Setup
- ngrok used to expose local Jenkins server
- GitHub webhook configured to trigger Jenkins automatically

## 📸 Screenshots
(Add Jenkins job success + deployed UI screenshots)

## 🚀 Future Enhancements
- Add staging and production environments
- Dockerize the application
- Implement Jenkins Pipeline (Jenkinsfile)
- Add monitoring and notifications

