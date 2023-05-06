# Kubernetes Cheat Sheet

## Pod Management

| Code Snippet | Description |
| ------------ | ----------- |
| `kubectl run pod --image=image` | Create a new pod |
| `kubectl delete pod pod` | Delete a pod |
| `kubectl get pods` | List all pods in the current namespace |

## Deployment Management

| Code Snippet | Description |
| ------------ | ----------- |
| `kubectl create deployment --image=image deployment` | Create a new deployment |
| `kubectl delete deployment deployment` | Delete a deployment |
| `kubectl get deployments` | List all deployments in the current namespace |

## Service Management

| Code Snippet | Description |
| ------------ | ----------- |
| `kubectl expose deployment deployment --port=port` | Expose a deployment as a service |
| `kubectl delete service service` | Delete a service |
| `kubectl get services` | List all services in the current namespace |

## Configuration Management

| Code Snippet | Description |
| ------------ | ----------- |
| `kubectl apply -f config.yml` | Apply a configuration file to the current namespace |
| `kubectl get configmaps` | List all ConfigMaps in the current namespace |
| `kubectl get secrets` | List all secrets in the current namespace |
