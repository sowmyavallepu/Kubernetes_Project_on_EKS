# Install EKS

Please follow the prerequisites doc before this.

## Install using Fargate

```
eksctl create cluster --name demo-cluster --region us-east-1 --fargate
```

# Update kubeconfig to use kubectl with the EKS cluster

```
aws eks update-kubeconfig --name demo-cluster --region us-east-1
```

## Delete the cluster

```
eksctl delete cluster --name demo-cluster --region us-east-1
```
