# k8s single redis persistence

### create storage ssd in gcp gke
kubectl apply -f storage-pvc.yaml

### deploy redis
kubectl apply -f redis.yaml
