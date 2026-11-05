# Cloud DevOps Demo

A small status page packaged with Docker and deployed to a local Kubernetes cluster using Minikube.

## Current setup

- Docker image: cloud-devops-demo:1.0
- Kubernetes Deployment: two replicas
- Kubernetes Service: NodePort
- Local cluster: Minikube

## Planned cloud stage

- Use GitHub Actions to build and publish the image to Amazon ECR.
- Run the image with Amazon ECS Fargate.
- View container logs in CloudWatch.




