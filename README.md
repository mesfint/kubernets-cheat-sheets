# Kubernetes Cheat Sheet


## Cluster Management Commands

| Snippet Command | Description |
| --- | --- |
| `kubectl version` | Display the Kubernetes version |
| `kubectl cluster-info` | Display information about the Kubernetes cluster |
| `kubectl config view` | Display the Kubernetes configuration file |
| `kubectl apply` | Apply a configuration to a Kubernetes cluster |
| `kubectl get` | Display Kubernetes resources |
| `kubectl describe` | Display detailed information about a Kubernetes resource |
| `kubectl delete` | Delete a Kubernetes resource |

## Pod Management

| Code Snippet | Description |
| ------------ | ----------- |
| `kubectl run pod --image=image` | Create a new pod |
| `kubectl delete pod pod` | Delete a pod |
| `kubectl get pods` | List all pods in the current namespace |
| `kubectl describe pod` | Display detailed information about a pod |
| `kubectl logs` | Display logs from a pod |
| `kubectl exec` | Execute a command inside a pod |

## Deployment Management

| Code Snippet | Description |
| ------------ | ----------- |
| `kubectl create deployment --image=image deployment` | Create a new deployment |
| `kubectl delete deployment deployment` | Delete a deployment |
| `kubectl get deployments` | List all deployments in the current namespace |
| `kubectl scale` | Scale a deployment |
| `kubectl rollout` | Manage rollouts of a deployment |
| `kubectl expose` | Expose a deployment as a service |

## Service Management

| Code Snippet | Description |
| ------------ | ----------- |
| `kubectl expose deployment deployment --port=port` | Expose a deployment as a service |
| `kubectl delete service service` | Delete a service |
| `kubectl get services` | List all services in the current namespace |

## Namespace Management Commands

| Snippet Command | Description |
| --- | --- |
| `kubectl create namespace` | Create a namespace |
| `kubectl get namespaces` | Display namespaces in a Kubernetes cluster |
| `kubectl describe namespace` | Display detailed information about a namespace |
| `kubectl delete namespace` | Delete a namespace |

## Configuration Management

| Code Snippet | Description |
| ------------ | ----------- |
| `kubectl apply -f config.yml` | Apply a configuration file to the current namespace |
| `kubectl get configmaps` | List all ConfigMaps in the current namespace |
| `kubectl get secrets` | List all secrets in the current namespace |
