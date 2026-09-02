# Kubernetes Manifests

This folder contains the Kubernetes configuration files used to deploy the React application to Amazon EKS.

Files:
- deployment.yaml
- service.yaml

Deployment Features:
- 2 Replica Pods
- LoadBalancer Service
- Container Image from Amazon ECR

The Jenkins pipeline automatically updates the deployment when new code is pushed to GitHub.
