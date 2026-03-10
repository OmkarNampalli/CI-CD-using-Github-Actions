# CI/CD using Github Actions

## Project Overview

This project demonstrates a complete **CI/CD pipeline for a Node.js application**, showcasing how modern DevOps practices can be used to automate building, containerizing, and deploying applications to a Kubernetes cluster.

A demo **Node.js application** is used as the base application. The project integrates **GitHub Actions** to implement a Continuous Integration (CI) pipeline that automatically builds the application and creates a Docker image whenever changes are pushed to the repository. The built image is then pushed to **Docker Hub** for storage and distribution.

For deployment, a local Kubernetes environment is set up using **Minikube**. The application is deployed to the cluster using Kubernetes **Deployment** and **Service** manifests. The Deployment ensures the application runs reliably inside containers, while the Service exposes the application so it can be accessed externally.

This project highlights the workflow of:

* Automating builds with GitHub Actions
* Containerizing applications using Docker
* Publishing images to Docker Hub
* Deploying containerized applications to a Kubernetes cluster using Minikube
* Managing application lifecycle with Kubernetes Deployment and Service resources

Overall, the repository serves as a practical example of implementing a simple end-to-end DevOps pipeline for containerized applications.
