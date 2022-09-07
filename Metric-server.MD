# Metric server is required for Horizontal Pod Autoscaler

## What is Metric Server?
```sh
It collects metrics like CPU, memory or Disk IO consumption for containers or nodes, from the Summary API, exposed by Kubelet on each node.
```

## Clone Metric-server helm chart on K8 Master
```sh
git clone https://github.com/mnforba/metric-server.git OR 
use: kubectl apply -f https://github.com/kubernetes-sigs/metrics-server/releases/latest/download/high-availability.yaml
```

## Create Metric Server
```sh
kubectl create -f .
kubectl top pods
kubectl top nodes
```
