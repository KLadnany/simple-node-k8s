# Node.js App for Kubernetes

Une simple app HTTP Node.js déployée sur Kubernetes.

## Utilisation

```bash
docker build -t kamaljuv/node-k8s-app .
docker push kamaljuv/node-k8s-app

kubectl apply -f k8s/deployment.yaml
kubectl apply -f k8s/service.yaml
