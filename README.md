# Software Engineering in Practice — Assignment 1 (2026)
## Ιωάννα Γιαγιά (t8230022)

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/IoannaGiag/seip_assignment_1_2026
```
### 2. Start Minikube

```bash
minikube start
```
### 3. Apply the Kubernetes manifests:

```bash
kubectl apply -f k8s/
```
### 4. Verify that all resources are running:

```bash
kubectl get all
kubectl get configmap,secret
```

### 5. Access the application using port forwarding:

```bash
kubectl port-forward service/echo-api-service 8080:80
```
### 6. Open the application in browser
http://localhost:8080/
http://localhost:8080/secure-config

