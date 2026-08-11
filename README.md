# CI/CD Pipeline & OpenShift Deployment Project

## Project Overview
This project sets up an automated CI/CD pipeline for a cloud-native microservice. It uses GitHub Actions for continuous integration (linting and unit testing) and Tekton / OpenShift Pipelines for cloud-native deployment.

## Key Features
* **Code Linting:** Evaluated using `flake8` / `eslint`
* **Unit Testing:** Executed using `nose` / `jest`
* **Continuous Delivery:** OpenShift Tekton pipelines with Persistent Volume Claims (PVC)
