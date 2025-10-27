# kubernetes-cluster
Task 5: Kubernetes Cluster with Minikube
Objective
Deploy and manage apps in Kubernetes using Minikube

Tools
Minikube
kubectl
Docker
Kubernetes

Steps Completed
Installed Minikube & kubectl
Started Kubernetes cluster with Minikube
Created deployment.yaml for Nginx app
Created service.yaml to expose the app
Deployed to Kubernetes cluster
Verified pods and services
Scaled deployment from 3 to 5 replicas

Files
deployment.yaml - Kubernetes deployment config
service.yaml - Service config to expose deployment

Commands Used
bash
minikube start --driver=docker
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl get pods
kubectl get services
kubectl scale deployment nginx-deployment --replicas=5
minikube service nginx-service
Pods running successfully

Services list showing LoadBalancer

Scaled deployment verification

What I Learned
Kubernetes basics (pods, deployments, services)

Local cluster setup with Minikube

Application deployment and scaling

Service exposure and management

