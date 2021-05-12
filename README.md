# MONGO-DB & MONGO-EXPRESS K8S

This is my simple mongodb and mongo express deployment using kubernetes via minikube.

## Walkthrough

```bash
kubectl apply -f mongodb-secret.yaml
kubectl apply -f mongodb-deployment.yaml
kubectl apply -f mongodb-configmap.yaml
kubectl apply -f mongo-express.yaml

# ACCESS MONGO EXPRESS PAGE
minikube service mongodb-express-service
```
