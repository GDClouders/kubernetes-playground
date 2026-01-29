
# Kubernetes kubectl Commands

## Run nginx container
```bash
kubectl run nginx-pod --image=nginx
```

## Apply pod from YAML file
```bash
kubectl apply -f pod.yaml
```

## Get pods
```bash
kubectl get pods
```

## Create pod
```bash
kubectl create -f pod.yaml
```

## Scale deployment
```bash
kubectl scale deployment nginx-deployment --replicas=3
```

## Create namespace
```bash
kubectl create namespace my-namespace
```

## Create pod in specific namespace
```bash
kubectl run nginx-pod --image=nginx --namespace=my-namespace
```

## Get pods from specific namespace
```bash
kubectl get pods -n my-namespace
```

## Get pods from all namespaces
```bash
kubectl get pods --all-namespaces
```
