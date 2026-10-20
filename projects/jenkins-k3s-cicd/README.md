# End-to-End CI/CD Pipeline on AWS

## Project Overview

An end-to-end CI/CD project using Jenkins, Maven, Docker, Docker Hub, and Kubernetes (K3s) on AWS EC2.

The goal is to automate application testing, container image creation, and deployment to a Kubernetes cluster.

## Technologies Used

- AWS EC2
- Ubuntu Linux
- Jenkins
- Java 21 and Maven
- Docker and Docker Hub
- Kubernetes (K3s)
- Git and GitHub

## Architecture

GitHub → Jenkins → Maven Tests → Docker Build → Docker Hub → Kubernetes Deployment

## Infrastructure

- One K3s master node
- Two worker nodes
- Jenkins controller on the master
- Jenkins build agents on the workers
- Application deployment with two replicas

## Key Learning Outcomes

- CI/CD pipeline configuration
- Automated application testing and packaging
- Container image build and publishing
- Kubernetes deployment and health checks
- Jenkins credentials and agent troubleshooting

## Source Repository

[View the original project on GitHub](https://github.com/rakesh-cloudops/ci-cd-jenkins-k3s-project)

## Notes

This documentation describes the project setup and intended workflow. Refer to the source repository and pipeline configuration for the exact implementation details.
