# DevOps Portfolio: NodeJS CI Pipeline with Jenkins

Welcome to my **DevOps Portfolio**! This repository showcases a **NodeJS application** that demonstrates a complete **CI pipeline** setup using **Jenkins**. As part of my journey towards becoming a DevOps professional, this project highlights my ability to build, test, dockerize, and deploy applications efficiently using automation practices.

## Project Overview

This project is a **NodeJS application** that lists developers and their associated projects. The focus is on automating the development process through **Jenkins pipelines** to ensure code quality and continuous deployment.

## Features and Workflow

### 1. Dockerization of NodeJS App
- The NodeJS application has been dockerized to enable consistent environment setup across different stages (development, testing, and production).
- A `Dockerfile` is created to package the application into a Docker image.

### 2. Continuous Integration Pipeline
- A Jenkins pipeline is configured to automate the build, test, and deployment process.

#### Pipeline Stages:
- **Version Increment**: Automatically increment the application version and the Docker image version.
- **Testing**: Execute automated tests to ensure code stability and prevent regression.
- **Build and Push Docker Image**: Build the Docker image and push it to a Docker repository for easy deployment.
- **Git Commit & Push**: Commit the version increment back to the Git repository.

### 3. Manual Deployment
- Once the pipeline successfully runs, the latest Docker image is deployed manually to a Droplet server. This ensures that the latest working version is available in the production environment.

### 4. Jenkins Shared Library
- To promote code reusability, a **Jenkins Shared Library** has been extracted. This allows other projects to easily reuse the logic for CI/CD automation.

---

## Technologies Used
- **NodeJS**: The backend framework used to build the application.
- **Docker**: To containerize the NodeJS application for consistent deployments.
- **Jenkins**: For automating the CI/CD pipeline.
- **Git**: Version control system for tracking code changes.
- **Jenkins Shared Library**: For reusable pipeline logic.

---

## Future Enhancements

- **Automated Deployment**: Implement an automated deployment step after successful tests and builds.
- **Monitoring and Alerts**: Integrate tools for real-time monitoring and alerting in case of pipeline or deployment failures.
- **Kubernetes Integration**: Extend deployment strategy to Kubernetes for better scaling and management.

---

## Conclusion

This repository showcases my expertise in setting up a CI pipeline with **Jenkins** for a **NodeJS** project, complete with Dockerization, automated testing, and version control. I hope this project demonstrates my DevOps skills and serves as a valuable addition to my portfolio.

**Thank you for visiting my repository! 😊**

