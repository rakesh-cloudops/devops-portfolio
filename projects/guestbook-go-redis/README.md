# Multi-Tier Guestbook — Go, Redis & Kubernetes

## Overview
A practice project demonstrating a Go web application connected to Redis and deployed using Kubernetes manifests.

## Technologies
- Go
- Docker
- Kubernetes
- Redis
- Make

## Architecture
Users → Guestbook Service → Go Application Pods → Redis

The repository includes manifests for the application and Redis components. Check the manifests for the exact workload types and service configuration.

## Learning Areas
- Go HTTP handlers
- Redis data operations
- Docker image builds
- Kubernetes Services and workload controllers
- Multi-tier application deployment

## Build
```bash
git clone https://github.com/rakesh-cloudops/guestbook-go-practice.git
cd guestbook-go-practice
docker build -t guestbook-go:local .
```

## Kubernetes
Review image names and manifest settings before deployment. Apply Redis resources before deploying the application, then inspect pods and services with `kubectl`.

Do not expose debugging endpoints or sensitive environment variables publicly.

## Original Repository
https://github.com/rakesh-cloudops/guestbook-go-practice
