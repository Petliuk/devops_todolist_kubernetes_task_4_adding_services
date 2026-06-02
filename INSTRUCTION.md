# ToDo App Kubernetes Testing Guide

## 1. Apply all manifests

```bash
kubectl apply -f namespace.yml
kubectl apply -f todoapp-pod.yml
kubectl apply -f todoapp-pod-2.yml
kubectl apply -f service-clusterip.yml
kubectl apply -f service-nodeport.yml
kubectl apply -f busybox.yml