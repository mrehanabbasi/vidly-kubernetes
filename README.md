## Vidly Video Rental App

Deployment of vidly app using Kubernetes.

### Running the app

Please run the following commands in the order after starting minikube and navigating to the project directory:

```kubectl apply -f namespace.yaml
kubectl apply -f frontend.yaml
kubectl apply -f db.yaml
kubectl apply backend.yaml
```

Run the folliwing command to get minikube cluster's IP and copy it:

```
minikube ip
```

After all the pods are up, navigate to `<YOUR_CLUSTER_IP>:32000` to run the app.
