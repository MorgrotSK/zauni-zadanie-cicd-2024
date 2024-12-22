# CI/CD Pipeline Overview

This project integrates **CI pipelines** with **GitHub Actions** for both the frontend and backend, and **CD pipelines** using **Tekton** for deployment.

## CI Pipeline (GitHub Actions)

The CI pipelines are defined and integrated directly within the respective repositories on GitHub:

### Frontend CI Pipeline

- **Repository**: [zauni-zadanie-appfrontend-2024](https://github.com/MorgrotSK/zauni-zadanie-appfrontend-2024)
- **Purpose**: This CI pipeline is responsible for building, testing, and deploying the frontend application. It ensures that every change made to the frontend repository is tested and packaged correctly.

### Backend CI Pipeline

- **Repository**: [zauni-zadanie-appbackend-2024](https://github.com/MorgrotSK/zauni-zadanie-appbackend-2024)
- **Purpose**: Similar to the frontend, this CI pipeline automates the build, test, and deployment processes for the backend application, ensuring that any changes made to the backend repository are thoroughly tested and packaged for deployment.

### CD Pipeline
The CD pipeline, **Tekton Pipelines** contained within here and needs to be deployed into kubernets cluster.

## Repository Links

- [Frontend GitHub Repository](https://github.com/MorgrotSK/zauni-zadanie-appfrontend-2024)
- [Backend GitHub Repository](https://github.com/MorgrotSK/zauni-zadanie-appbackend-2024)
