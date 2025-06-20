# Kubescope Exercises

## Pre-requisites

- [kubectl](https://kubernetes.io/docs/tasks/tools/#kubectl)
- A running [minikube](https://minikube.sigs.k8s.io/docs/start/) cluster
- A **Namespace** `kubescope-ns` exists in the cluster
```bash
kubectl create namespace kubescope-ns
```

## Exercises

1. [Create Pod](./01-pod-local-access)

1. [Create Deployment](./02-deployment/)

1. [Create Deployment with environment variables](./03-env-variables/)

1. [Create Deployment with ConfigMap as environment variables](./04-configmap-as-env/)

1. [Create Deployment with ConfigMap as configuration file](./05-configmap-as-file/)

1. [Create Deployment with secret as environment variables](./06-secrets-as-env/)

1. [Create InitContainer, write to shared volume](./07-init-container/)

1. [Create Postgres Deployment and Service, and connect Pods](./08-database/)

1. [Add data persistency to Pod](./09-database-persistence/)
