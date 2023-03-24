
## Kubernetes Tutorial

### Install Minikube

https://minikube.sigs.k8s.io/docs/start/

### Start Minikube

`minikube start --driver=docker`

### Get all components that are inside the cluster

`kubectl get all`

### Get pods in all namespaces

`kubectl get pods -A`

### Create Kubernetes Secret

`kubectl apply -f mongo-secret.yaml`

### Get Kubernetes Secret

`kubectl get secret`

### Create MongoDB Deployment

`kubectl apply -f mongo.yaml`

### Get Kubernetes Service

`kubectl get service`

### Describe Kubernetes Service

`kubectl describe service <service-name>`

### Assign External IP Address to Kubernetes Service via Minikube

`minikube service <service-name>`