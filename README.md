

# Kubernetes Deployment and Service Example

This repository provides an example YAML file that demonstrates the creation of various Kubernetes resources including a Pod, Deployment, Service, ClusterIP, Role, and RoleBinding.

## Contents

- [Deployment](https://github.com/adayahasha/yaml-kubernetes/blob/main/Kube_Demo_Files/redis-deployment.yml)
- [Service](https://github.com/adayahasha/yaml-kubernetes/blob/main/Kube_Demo_Files/redis-service.yml)
- [ClusterIP](https://github.com/adayahasha/yaml-kubernetes/blob/main/cluster_ip.yml)
- [Cluster-Role](https://github.com/adayahasha/yaml-kubernetes/blob/main/cluster-role.yaml)
- [Cluster-Role-Binding](https://github.com/adayahasha/yaml-kubernetes/blob/main/cluster-role-binding.yaml)

## Deployment

The `deployment.yaml` file contains the configuration for a Deployment resource. It defines a replica set of Pods running a Redis application. To create the deployment, run the following command:

```bash
kubectl apply -f deployment.yaml
